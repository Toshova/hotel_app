<template>
    <div class="wrapper">
     <div class="img_wrapper">
         <img src="/download_1.png">
         <div class="frame_529">  
         </div>
         <div class='rectangle_545'>
            <div class="bell_wrapper" >
                <img id="bell_logo_big" src="/bell_logo_big.png">
            </div>
                 
                 <div>
                     <p class="pms_wrapper">
                     <span style='color: #003D99'>P</span>roperty
                     <span style='color: #003D99'>M</span>anagement
                     <span style='color: #003D99'>S</span>ystem
                     </p>
                 </div>
                 <div class="input_wrapper">
                     <input class="text-field-login" type="text" placeholder="Введите логин" >
                     <input class="text-field-password" type="text" placeholder="Введите пароль">
                 </div>  
                 <div class="btn_wrapper">
                    
                    <nuxt-link exact to="/product_key">
                        <button id="btn_1">
                            <p>Обучающие ролики</p>
                        </button>
                    </nuxt-link>
                 
                 <nuxt-link exact to="/">
                 
                 <button id="btn_2">
                     <p>Войти</p>
                 </button>
                 </nuxt-link>
                 
             </div>
         </div>
     </div>
     </div>
     
 </template>
 
 
 
  <style scoped>
 
  p {
    font-family: 'SF Pro Display', sans-serif;
    font-weight: 600px;
    font-size: 17px;
    line-height: 20px;
    text-align: center;  
  }
 .wrapper {
    display: flex;
    background-color: #091C31;
    align-items: center;
    justify-content: center;
 }
 .img_wrapper{
    width: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
 }
 .wrapper img {
    display: flex;
    min-height:100%;
    width: 100%;
    opacity: 40%;   
 }
 
 .frame_529 {
    display: flex;
    align-items: center;
    justify-content: center;
    position: fixed;
    width: 468px;
    height: 412px;
    border-radius: 8px;
    background: 
    linear-gradient(#FBFDFFA6, #FBFDFFA6) padding-box,
    linear-gradient(to right,#FFFFFF, #091C3199 60%) border-box;
    border: 2px solid transparent;
    opacity: 65%;
 }
 
 .rectangle_545{ 
    display: flex;
    background-color: transparent;
    position: fixed;
    width: 472px;
    height: 416px;
    opacity: 1;
    flex-direction: column;
    align-items: center;
 }
 .bell_wrapper{
    margin-top: 48px;
 }
 #bell_logo_big {
    opacity: 1; 
 }
 .pms_wrapper {
    width: 229px;
    height: 20px;
    color: #08162B;
    margin-left: auto;
    margin-right: auto;
    margin-top: 12px;
    color: #08162B;
  }
 
  .input_wrapper{
    display: flex;
    flex-direction: column;
    margin-left: auto;
    margin-right: auto;
     
  }
  .text-field-login {
    width: 420px;
    height: 48px; 
    border-radius: 8px;
    background-color:  white;
    box-shadow: 0 2px 6px#08162B2E;
    background: #FFFFFF url("/icons.png");
    background-repeat: no-repeat;
    background-position-x: 380px;
    background-position-y: 50%;
    border: 1px solid #D5D8DD;
    padding-left: 16px;
    outline:none;
    margin-top: 48px;
  }
 
  .text-field-password {
    margin-top: 24px;
    border: 1px solid #D5D8DD;
    background-color: #FFFFFF;
    box-shadow: 0 2px 6px #08162B2E; 
    background: #FFFFFF url("/lock.png");
    background-repeat: no-repeat;
    background-position-x: 380px;
    background-position-y: 50%;
    width: 420px;
    height: 48px; 
    border-radius: 8px;
    padding-left: 16px;
    outline:none;
  }
  .btn_wrapper{
     display: flex;
     height: 100vh;
     align-items: center;     
  }
 
  button {

     width: 180px;
     height: 48px;
     
 }
 #btn_1 {
     margin-left: 0px;
     color: #08162B;
 }
 
 #btn_2 {
     background-color: #0066FF;
     color: #FFFFFF;
     border-radius: 8px;
     margin-left: 60px;     
 }
 </style>
 
 
 <script>
 export default {
     layout: 'empty'
 }
 </script>