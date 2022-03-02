<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
 
  <navbar></navbar>
  <footer></footer>
   
</template>

<script>

import navbar from './components/navbar.vue'
import footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
   
    navbar,
    footer
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
