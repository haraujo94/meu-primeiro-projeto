<template>
  <div class=" cadastro-cliente">
    <h1>Cadastro de Cliente</h1>
    <img src="../assets/carros.png.jpg">
    
    <form @submit.prevent="submitForm">
      <div>

        <label for="nome"> Nome:</label>
        <input type="text" placeholder="Nome completo do cliente" 
        id="nome" v-model="m_nome" required>
      </div>
      
      <div>

        <label for="email"> Email:</label>
        <input type="email" placeholder="Endereço eletronico"  
        id="email" v-model="m_email" required>
      </div>

      <div>
        <label for="cep"> Cep:</label>
        <input type="text" placeholder="Codigo endereço postal"
         id="CEP" v-model="m_cep" required>
      </div>

      <div>
        <label for="endereco"> Endereço:</label>
        <input type="text" id="endereco" v-model="m_endereco" required>
      </div>


      <button type="submit"> Cadastrar</button>
      </form>
     </div>
</template>

<script>
export default {
  name: 'CadastroCliente',

 
};

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cadastro-cliente{

  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 60px ;
}
.form{
  padding: 60px
}
</style>
