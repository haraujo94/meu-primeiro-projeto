<template>
  <div class=" cadastro-cliente">
    <h1>Cadastro de Cliente</h1>
    <form>
      <div>

        <label for="nome"> Nome:</label>
        <input type="text" id="nome" v-model="nome" required>
      </div>
      
      <div>

        <label for="email"> Email:</label>
        <input type="email" id="email" v-model="email" required>
      </div>

      <div>
        <label for="cep"> Código de Endereço Postal</label>
        <input type="text" id="cep" v-model="cep" required>
      </div>

      <button type="submit"> Cadastrar</button>
      </form>
     </div>
</template>

<script>
export default {
  name: 'CadastroCliente',
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
h1{
  color: blueviolet;
  font-size: 40px;
}
</style>
