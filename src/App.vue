<template>
  <img alt="Vue logo" src="./assets/logo.png">
  
  <HelloWorldNew msg="Bem Vindo ao seu aplicativo vue.js"/>
  <ListadeClientes/>
</template>

<script>

import HelloWorldNew from './components/HelloWorldNew.vue'
import ListadeClientes from './components/ListaDeClientes.vue'


export default {
  name: 'App',
  components: {
     HelloWorldNew, ListadeClientes
  }
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
