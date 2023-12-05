<template>
  <div class="wrapper">  
        <side-bar/>
      <div class="main_wrapper">
        <nav-bar/>   
        <main>
        <Nuxt /> 
      </main>
      </div>   
  </div>    
</template>

<script>


import sideBar from '../components/side-bar.vue';
import navBar from '../components/nav-bar.vue';

export default {
  sideBar, navBar
}

</script>

<style>
.wrapper { 
  display: flex;
  width:100%; 
  
  
}

main{
  background-color: #F0F6FF;
  border: transparent solid 12px;
  
  
}

.main_wrapper {
  display: flex;
  flex-direction: column;  
  width: 100%;
  height:100%;
  margin-left: 220px;  
}


</style>