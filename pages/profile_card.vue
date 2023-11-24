<template>
    <div class="l_rect">
        <img id="backdrop" src="/Rectangle_29.png" >
        <div class="s_rect">
            <div>
                <div class="img_wrap">
                    <img src="/l_brun.png"> 
                </div>

                <p class="m_letters">Менеджер:</p>
                <p class="m_letters" id="all_caps">ABDUMALIKOVA GULCHEHRA ABDUVORISOVNA</p>
                <p class="s_letters">Начало смены</p>
                <p class="digit" id="digit_blue">09:00 10.01.2021</p>
                <p class="s_letters">Продолжительность смены</p>
                <p class="digit">03:45 мин</p>
                <p class="s_letters">Рекорд</p>
                <p class="digit">17:36 мин</p>
            </div>
        
            <div class="btn_wrapper">
                <nuxt-link exact to="/profile">
                    <button>
                        <img src="/pensil_icon.png"><p class="text_btn">Изменить</p>
                    </button>
                </nuxt-link>

                <nuxt-link exact to="/">
                    <button>
                        <img src="/exit_icon.png"><p class="text_btn">Выйти</p>
                    </button>
                </nuxt-link>
            </div>
        </div>
    </div>
</template>

<style scoped>
.l_rect {
    display: flex;
    width: 100%;
    height:100vh;   
}
#backdrop{
    width: 100%;
    height:100%; 
}


.img_wrap{
    display: flex;
    justify-content: center;
    width: 312px;
    height: 264px;
    margin-top: 24px;
    margin-bottom: 13px;
    
}
.s_rect {
    display: flex;
    flex-direction: column;
    position: absolute;
    justify-content: space-between;
    width:312px;
    height:100%;
    background-color: #FFFFFF;
    right: 0px;
    border-radius: 8px 0px 0px 8px;
    font-family: 'SF Pro Display', sans-serif;
    text-align: center;  
}
.m_letters{
    font-weight: 500;
    font-size: 15px;
    line-height: 20px;
    color: #8F97A3;
}
.s_letters{
    font-weight: 500;
    line-height: 20px;
    color: #8F97A3;
    font-size: 13px;
}
.digit{
    font-weight: 600;
    font-size: 22px;
    line-height: 20px;
    color: #08162B;
    margin-top: 6px;
    margin-bottom: 24px;
}

#digit_blue{
    color: #0066FF;
 }

#all_caps{
    color:#08162B;
    margin-top: 11px;
    margin-bottom: 32px;
}
.btn_wrapper{
    display: flex;
    justify-content: space-around; 
    flex-direction: row;
    align-items: flex-end;
    margin-bottom: 32px;    
}
 
button {
    display:flex;
    align-items:center;
    justify-content: center;
    width: 120px;
    height: 40px;
    border: 1px #0066FF solid;
    border-radius: 8px;
    color: #0066FF;
    font-weight: 500;
    font-size: 13px;
    line-height: 18px;
    
}
.text_btn {
    margin-right: 8px;
    margin-left: 8px;
}
 
</style>

<script>

export default {
    layout: 'empty'
}

</script>