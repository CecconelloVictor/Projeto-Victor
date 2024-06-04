<template>
  <div>
    <h2>Lista de Clientes</h2>
    <ul>
      <li v-for="cliente in clientes" :key="cliente.id">{{ cliente.nome }}</li>
    </ul>
    <button @click="adicionarCliente">Adicionar Cliente</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      clientes: [
        { id: 1, nome: 'Cliente 1' },
        { id: 2, nome: 'Cliente 2' },
        { id: 3, nome: 'Cliente 3' }
      ]
    };
  },
  methods: {
    adicionarCliente() {
      const novoCliente = {
        id: this.clientes.length + 1,
        nome: `Novo Cliente ${this.clientes.length + 1}`
      };
      this.clientes.push(novoCliente);
    }
  }
};
</script>

<style scoped>
/* Estilos específicos para ListaDeClientes.vue */
</style>