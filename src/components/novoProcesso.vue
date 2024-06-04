<template>
  <div>
    <h2>Processos</h2>
    <input v-model="novoProcesso" placeholder="Novo Processo" />
    <button @click="adicionarProcesso">Adicionar Processo</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      novoProcesso: "",
      processos: []
    };
  },
  methods: {
    adicionarProcesso() {
      if (this.novoProcesso.trim() !== "") {
        this.processos.push(this.novoProcesso);
        this.novoProcesso = "";
      }
    }
  }
};
</script>

<style scoped>
/* Estilos específicos para Processos.vue */
</style>