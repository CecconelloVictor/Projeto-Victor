<template>
  <div>
    <h2>Direito Penal</h2>
    <textarea v-model="descricaoCrime" placeholder="Descrição do Crime"></textarea>
    <button @click="registrarCrime">Registrar Crime</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      descricaoCrime: ""
    };
  },
  methods: {
    registrarCrime() {
      console.log("Crime registrado:", this.descricaoCrime);
      // Lógica para enviar dados do crime para o servidor
    }
  }
};
</script>

<style scoped>
/* Estilos específicos para DireitoPenal.vue */
</style>
