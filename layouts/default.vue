<template>
  <div>
    <div class="container"> 
      <side-bar/>
      <div class="main_wrapper"> 
        <nav-bar/>

        <main>
        <Nuxt /> 
      </main>
      </div>
      
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
main{
  border: #F0F6FF 12px solid;
}

.container {
  height: 100%; 
  display: flex;
}

.main_wrapper {
  height: 100%; 
  width:100%;
  flex-direction: row;       
}

.main_wrapper main {
  width:100%;
  height:100%;
}
</style>