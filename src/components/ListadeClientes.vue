<template>
  <div>
    <label>Lista de Clientes</label>
       <select name="ListaClientes" id="ListaClientes">
        <option value="">Selecione</option>
        <option value="Cliente1">Fiat</option>
        <option value="Cliente2">Chevrolet</option>
        <option value="Cliente3">Toyota</option>
        <option value="Cliente4">Volkswagen</option>
        <option value="Cliente5">Citroen</option>
        
        

    </select>
  </div>
</template>

<script>
export default {
  name: 'ListadeClientes',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
label {
  color: black;
  font-size: 20px;
}
select{
  color: white;
  background-color: black;
  font-size: 20px;
}
</style>
