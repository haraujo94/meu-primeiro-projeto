<template>
  <div>
    <label> Carburador a Diesel</label>
  </div>

<ObjetoArranque/>


</template>

<script>
//Pesquisar sobre caminho relativo e caminho absoluto

import ObjetoArranque from './ArranqueDoCarro.vue';

export default {
  
name: 'Carburador',
components: {

  ObjetoArranque,

},
props: {


  msg: String
}



}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
