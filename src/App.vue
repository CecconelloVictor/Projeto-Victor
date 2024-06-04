<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Seja Bem Vindo ao escritório de Advogados CECCONELLO&OLIVEIRA ADVOGADOS ASSOCIADOS"/>
  <calcularImpostoDeRenda/>
  <descricaoCrime/>
  <ListaDeClientes/>
  <novoProcesso/>
  
</template>

<script>
import calcularImpostoDeRenda from './components/calcularImpostoDeRenda.vue'
import descricaoCrime from './components/descricaoCrime.vue'
import HelloWorld from './components/HelloWorld.vue'
import ListaDeClientes from './components/ListaDeClientes.vue'
import novoProcesso from './components/novoProcesso.vue'

export default {
  name: 'App',
  components: {
 calcularImpostoDeRenda, descricaoCrime, HelloWorld, ListaDeClientes, novoProcesso,
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
