
<template>
  <view class="container">
    <text class="logininfo">LOGIN</text>
    <text class="info">E-MAIL:</text>
    <text-input class="input"/>
    <text class="info">SENHA:</text>
    <text-input class="input"/>
    <view class="userbtn1"> 
      <button class="login" title="Login" color="green"></button>
    </view>
    <view class="userbtn2">
      <button class="forgot" title="Esqueci minha senha" color="red"></button>
    </view>  
  </view>
</template>


<script>
export default {
  data() {
    return {
      email: "E-MAIL",
      senha: "SENHA",
    };
  },
  };
</script>


<style>

.userbtn1 {
  display: flex;
   margin: 20px;
          }

.userbtn2 {
  display: flex;
   margin: 20px;
          }

.container {
  background-color: white;
  align-items: center;
           }

.login {
  align-self: flex-start;
  margin: 15px 10px;
       }

.info {
  align-self: flex-start;
  padding: 10px;
  margin: 5px;
  font-size: 20px;
  font-weight: bold;
  font-style: italic;
  color:black;
      }
      
.logininfo {
  margin: 20%;
  font-size: 50px;
  color: black;
  font-style: italic;
  font-weight: bold;
          }

.input {
  width: 90%;
  margin: 10px 10px;
  border-radius: 2px;
  padding: 10px;
  border-width: 4;
       }
</style>