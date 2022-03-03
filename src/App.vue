<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  
  <navbar></navbar>
  <foot></foot>

   
</template>

<script>

import navbar from './components/navbar.vue'
import foot from './components/foot.vue'


export default {
  name: 'App',
  components: {
   
    navbar,
    foot
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
