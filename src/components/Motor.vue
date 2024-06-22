<template>
  <div>
    <label> Motor do carro</label>
    <select name="MotorCarro" id="MotorCarro">
        <option value="">Selecione</option>
        <option value="Tipo1">1.0</option>
        <option value="Tipo2">1.4</option>
        <option value="Tipo3">1.6</option>
        <option value="Tipo4">1.8</option>
        <option value="Tipo5">2.0</option>
        </select>
  </div>

<ObjetoArranque/>
<ObjetoCarburador/>


</template>

<script>

import ObjetoArranque from './ArranqueDoCarro.vue';
import ObjetoCarburador from './CarburadorDoCarro.vue';

export default {
  
name: 'MotorCarro',
components: {

  ObjetoArranque, ObjetoCarburador, 

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
  color: black;
}
select{
  color: white;
  background-color: black;
  font-size: 20px;
}
        
</style>
