<template>
 
  <Home msg="Welcome to Your Vue.js App"/>
  <div>
    <webapp-footer />
    </div>
</template>

<script>
import Home from './components/Home.vue'
import footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
  Home,
    'webapp-footer':footer,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
/*  text-align: center; */
  color: white;
/*  margin-top: 60px; */
}

body{
  
  background: green;
}
</style>
