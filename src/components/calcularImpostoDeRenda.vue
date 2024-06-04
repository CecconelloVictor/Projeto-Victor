<template>
  <div>
    <h2>Direito Trabalhista</h2>
    <label for="salario">Salário:</label>
    <input type="number" id="salario" v-model="salario" />
    <p>Imposto de Renda: {{ calcularImpostoDeRenda() }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      salario: 0  
    };
  },
  methods: {
    calcularImpostoDeRenda() {
      if (this.salario <= 2000) {
        return "Isento";
      } else if (this.salario <= 5000) {
        return "10%";
      } else {
        return "20%";
      }
    }
  }
};
</script>

<style scoped>
/* Estilos específicos para DireitoTrabalhista.vue */
</style>