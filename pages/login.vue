<template>

    <div class='rectangle_11'>

        <img src="/download_1.png">
        <div class="frame_529">

            <div class='rectangle_545'>
            </div>
        </div>

        <div class="data_wrapper">
            <img id="bell_logo_big" src="/bell_logo_big.png">

            <div>
                <p class="pms_wrapper">
                <span style='color: #003D99'>P</span>roperty
                <span style='color: #003D99'>M</span>anagement
                <span style='color: #003D99'>S</span>ystem
                </p>
            </div>
               
            <div >
                <input class="text-field-login" type="text" placeholder="Введите логин" >
                <input class="text-field-password" type="text" placeholder="Введите пароль">
            </div>  

            <div>
                <button class="btn_1">
                    <p>Обучающие ролики</p>
                </button>

                <nuxt-link exact to="/">
                <button class="btn_2">
                    <p>Войти</p>
                </button>
                </nuxt-link>
                
            </div>
            
            
        </div>
    </div  >
    
        
    
</template>

<script>
export default {
    layout: 'empty'
}

</script>

<style scoped>
 
button {
    width: 180px;
    height: 48px;
    margin-top: 200px;
}
.btn_1 {
    margin-left: 24px;
}

.btn_2 {
    margin-left:57px;
    background-color: #0066FF;
    color: #FFFFFF;
    border-radius: 8px;

}

.heading_3 {
    position:fixed;
    
}

.heading_3 p {
    width: 158px;
    height: 20px;
    border: 1px solid black;
    font-family: 'SF Pro Display', sans-serif;
    font-weight: 600px;
    font-size: 17px;
    line-height: 20px;
    text-align: center;
    color: #08162B; 
}
.rectangle_11 {
    position:fixed;
    width: 1600px;
    height: 900px;
    background-color: #091C31;
}
 .rectangle_11 img {
    
    opacity: 40%;
 }

 .frame_529{
    position: fixed;
    top: 242px;
    left: 564px;
    width: 472px;
    height: 416px;
    background: linear-gradient(#FFFFFF, #091C3199 60%);
    border-radius: 8px;
 }

.rectangle_545 {
    position: fixed;
    top: 244px;
    left: 566px;
    background-color:#FBFDFF;
    opacity: 65%;
    width: 468px;
    height: 412px;
    border-radius: 8px;
    border: 2px solid transparent;
}
.data_wrapper {
    background-color: transparent;
    position: fixed;
    top: 242px;
    left: 564px;
    width: 472px;
    height: 416px;
 }
#bell_logo_big {
    width: 126px;
    height: 52px;
    opacity:1;
    margin-top: 48px;
    margin-left: 171px;
}
 .pms_wrapper {
    width: 229px;
    height: 20px;
    font-family: 'SF Pro Display', sans-serif;
    font-weight: 600px;
    font-size: 17px;
    line-height: 20px;
    text-align: center;
    color: #08162B;
    margin-top: 12px;
    margin-left: 120px; 
 }

 .text-field-login {
    position: fixed;
    margin-top: 48px;
    margin-left: 24px;
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
 }

 .text-field-password {
    border: 1px solid #D5D8DD;
    background-color: #FFFFFF;
    box-shadow: 0 2px 6px #08162B2E;
    position: fixed;
    margin-top: 120px;
    margin-left: 24px;
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


</style>