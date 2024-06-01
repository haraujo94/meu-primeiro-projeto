<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    
    <h3>Menu</h3>
    <ul>
      <li><a href="link1" target="_blank" rel="noopener">Opção1</a></li>
      <li><a href="link2" target="_blank" rel="noopener">Opção2</a></li>
    </ul>
   
  </div>
</template>

<script>
export default {
  name: 'HelloWorldNew',
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
