<template>
  <div>
    <label> Arranque do Carro 4.0</label>
    <select name="ArranqueCarro" id="ArranqueCarro">
        <option value="">Selecione</option>
        <option value="Tipo1">Convencional</option>
        <option value="Tipo2">Alta Perfomance</option>
        <option value="Tipo3">Reduzido</option>
        </select>
  </div>
</template>

<script>


export default {
  
name: 'ArranqueCarro',

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
