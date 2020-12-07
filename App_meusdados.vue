<template>
  <view class="container">
    <text class="meusdados">MEUS DADOS</text>
    <text class="datauser">NOME:</text>
    <text-input class="input"/>
    <text class="datauser">E-MAIL:</text>
    <text-input class="input"/>
    <text class="datauser">CELULAR:</text>
    <text-input class="input"/>
    <text class="datauser">SEXO:</text>
    <text-input class="input"/>
    <text class="datauser">IDADE:</text>
    <text-input class="input"/>
    <view class="databtn1"> 
      <button class="atualizar" title="atualizar" color="green"></button>
    </view>
  </view>
</template>


<script>
export default {
  data() {
    return {
      nome: "NOME",
      email: "E-MAIL",
      celular: "CELULAR",
      sexo: "SEXO",
      idade: "IDADE"
    };
  },
  };
</script>


<style>

.databtn1 {
  display: flex;
   margin: 20px;
          }

.container {
  background-color: white;
  align-items: center;
           }

.atualizar {
  align-self: flex-start;
  margin: 15px 10px;
       }

.datauser {
  align-self: flex-start;
  padding: 10px;
  margin: 1px;
  font-size: 15px;
  font-weight: bold;
  font-style: italic;
  color:black;
      }
      
.meusdados {
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