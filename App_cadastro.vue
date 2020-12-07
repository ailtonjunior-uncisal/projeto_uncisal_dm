<template>
  <view class="container">
    <text class="cadastro">CADASTRO</text>
    <text class="caduser">NOME:</text>
    <text-input class="input"/>
    <text class="caduser">E-MAIL:</text>
    <text-input class="input"/>
    <text class="caduser">SENHA:</text>
    <text-input class="input"/>
    <text class="caduser">CELULAR:</text>
    <text-input class="input"/>
    <view class="cadbtn1"> 
      <button class="cadastrar" title="cadastrar" color="green"></button>
    </view>
  </view>
</template>


<script>
export default {
  data() {
    return {
      nome: "NOME",
      email: "E-MAIL",
      senha: "SENHA",
      celular: "CELULAR",
    };
  },
  };
</script>


<style>

.cadbtn1 {
  display: flex;
   margin: 20px;
          }

.container {
  background-color: white;
  align-items: center;
           }

.cadastrar {
  align-self: flex-start;
  margin: 15px 10px;
       }

.caduser {
  align-self: flex-start;
  padding: 10px;
  margin: 5px;
  font-size: 20px;
  font-weight: bold;
  font-style: italic;
  color:black;
      }
      
.cadastro {
  margin: 20%;
  font-size: 40px;
  color: black;
  font-style: italic;
  font-weight: bold;
          }

.input {
  width: 90%;
  margin: 6px 10px;
  border-radius: 2px;
  padding: 10px;
  border-width: 4;
       }
</style>