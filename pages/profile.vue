<template>
    <div class="wrapper">
        <div class="def" id="header">
            <nuxt-link exact to="/profile_card">
                <img src="/corner.png">
            </nuxt-link>
            <p>Мой профиль</p>
       </div>

       <hr>

       <div class="section_wrap">
        <div class="section_name">
            <p class="m_letters">ФИО</p>
            <img src="/pens_grey.png">
        </div>
        <div class="section_val">
            <p><span class="grey">Имя: </span> Gulchehra</p>
            <p><span class="grey">Фамилия: </span> Abdumalikova</p>
            <p><span class="grey">Отчество: </span> Abduvorisovna</p>
        </div>
       </div>

       <hr>

       <div class="section_wrap">
        <div class="section_name">
            <p class="m_letters">Логин и пароль</p>
            <img src="/pens_grey.png">
        </div>
        <div class="section_val">
            <p><span class="grey">Логин: </span> gulchehra@hotel.uz</p>
            <p><span class="grey">Пароль: </span> *************</p>
        </div>
        </div>

       <hr>

       <div class="section_wrap">
        <div class="section_name">
            <p class="m_letters">Контакты</p>
            <img src="/pens_grey.png">
        </div>
        <div class="section_val">
            
                <p><span class="grey">Номер телефона: </span> +998 9* ***-**-78</p>
            <p><span class="grey">Дополнительный номер телефона: </span> +998 9* ***-**-78</p>
            <p><span class="grey">E-mail адрес: </span> abdumalikovagul@testmail.com</p>
            
            
        </div>
       </div>
       
       <hr>

    
       <div class="section_wrap section_val">
        <p class="m_letters">Дополнительная информация</p>
        <p><span class="grey">Должность: </span> Менеджер</p>
        <p><span class="grey">Дата регистрации: </span> 23.08.2020 г</p>
       </div>

       <hr>

       <div class="section_wrap">
        <p class="m_letters">Фотография профиля</p>
        <div class="photo_section">
            <div class="photo_upload">
                <img src="/photo_upload.png">
                <p class="grey">Загрузить фото</p>
            </div>
            <img id="m_brun" src="/m_brun.png">
        </div>
        
       </div>
    </div>
</template>

<style scoped>
.section_val p {
    margin-bottom: 12px;
}
.wrapper{
    display:flex;
    width:100%;
    height: 958px;
    flex-direction: column;  
    font-family: 'SF Pro Display', sans-serif;  
}

p{
    font-weight: 500;
    font-size: 15px;
    line-height: 20px; 
}

.grey{
    color:#8F97A3;
}
.def{
    color:#8F97A3;
    display: flex;
    flex-direction: row;
    height: 60px;
    font-weight: 600;
    font-size: 22px;
    line-height: 20px;
    
}

.def p{
    margin-top: 16px
}
.def img{
    width:24px;
    height: 24px;
    margin-left: 16px;
    margin-right: 12px;
    margin-top: 14px;
}

.photo_upload{
    display: flex;
    width: 150px;
    height: 150px;
    flex-direction: column;
    border: #D5D8DD 2px dashed;
    border-radius: 8px;
    box-shadow: 0 2px 6px 0 #08162B2E;
    margin-right: 24px;
    align-items: center;
    
}

.photo_upload img{
    width: 60px;
    height: 60px;
    margin-top: 32px;
    margin-bottom: 14px;
}
.section_wrap{
    display: flex;
    flex-direction: column;
    margin: 24px 0 12px 24px;
}
.photo_section{
    display: flex;
}
.section_name{
    display: flex;
    justify-content: space-between;
}

.section_name img {
    width: 24px;
    height: 24px;
    margin-right: 24px;
}

.section_val{
    display: flex;
    flex-direction: column;
}
.m_letters{
    font-weight: 600;
    font-size: 17px;
    line-height: 20px;
    color: #8F97A3;
    margin-bottom: 24px;
}
#m_brun{
    width: 150px;
    height: 150px;
}
</style>

<script>
export default {
  name: 'IndexPage',
}
</script>