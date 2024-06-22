<template>
  <div>
    <label> Carburador a Diesel</label>
    <select name="CarburadorCarro" id="CarburadorCarro">
        <option value="">Selecione</option>
        <option value="Tipo1">Descendente</option>
        <option value="Tipo2">Horizontal</option>
        <option value="Tipo3">Ascendente</option>
        </select>
  </div>

</template>

<script>
//Pesquisar sobre caminho relativo e caminho absoluto
export default {
  
name: 'CarburadorCarro',
components: {

},
props: {


  msg: String
}



}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
label{
  font-size: 20px;
  color:black;
}
select{
  color: white;
  background-color: black;
  font-size: 20px;
}
</style>
