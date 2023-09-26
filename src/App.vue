<script setup>
// import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
   import Header from './components/Header/Header.vue'
   import Footer from './components/Footer/Footer.vue'
</script>

<template>
  <div class="wrapper">
    <Header></Header>
    <router-view></router-view>
  </div>
  <Footer></Footer>
    
</template>

<style scoped>
.wrapper{
  max-width: 1160px;
  margin: 0 auto;
}
</style>
