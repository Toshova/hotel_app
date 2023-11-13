<template>
  <div>
    <div class="side_nav"> 
      <side-bar/>
      <nav-bar/>
    </div>
    <div class="container">
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
body {
  width: 1600px;
  height: 900px; 
}

.side_nav {
  display: flex;
}

.container {
  position: absolute;
  top: 64px;
  left: 220px;
  width:1380px;
  height: 812px;
  border: 12px solid #F0F6FF;
  border-radius: 8px;
}
</style>