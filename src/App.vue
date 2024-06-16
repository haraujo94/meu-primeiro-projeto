<template>
  <img alt="Vue logo" src="./assets/logo.png">
  
  <HelloWorldNew msg="Bem Vindo ao seu aplicativo vue.js"/>
  <ListadeClientes/> 
  <Motor/>
  <ArranqueDoCarro/>

</template>

<script>

import HelloWorldNew from './components/HelloWorldNew.vue'
import ListadeClientes from './components/ListadeClientes.vue'
import Motor from './components/Motor.vue'
import ArranqueDoCarro from './components/ArranqueDoCarro.vue'

export default {
  name: 'App',
  components: {
     HelloWorldNew, ListadeClientes, Motor, ArranqueDoCarro,
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
