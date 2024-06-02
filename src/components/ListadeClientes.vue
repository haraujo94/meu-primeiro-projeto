<template>
  <div>
    <label>Lista de Clientes</label>
       <select name="ListaClientes" id="ListaClientes">
        <option value="">Selecione</option>
        <option value="Cliente1">Petrobrás</option>
        <option value="Cliente2">Vale do Rio Doce</option>
        <option value="Cliente3">Transpetro</option>

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
  color: #42b983;
  font-size: 14px;
}
select{
  color: black;
  background-color: green;
}
</style>
