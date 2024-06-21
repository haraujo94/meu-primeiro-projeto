<template>
  <CadastroCliente/>
  <ListadeClientes/> 
  <Motor/>
  <ArranqueDoCarro/>

</template>

<script>
import CadastroCliente from './components/CadastroCliente.vue'
import ListadeClientes from './components/ListadeClientes.vue'
import Motor from './components/Motor.vue'
import ArranqueDoCarro from './components/Motor.vue'


export default {
  name: 'App',
  components: {
    
  CadastroCliente, ListadeClientes, Motor, ArranqueDoCarro,
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
