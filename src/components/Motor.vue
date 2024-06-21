<template>
  <div>
    <label> Motor do carro</label>
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
  color: blue;
}
        
</style>
