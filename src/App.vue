<template>
   <webapp-header />    
  <Home msg="¡Bienvenido a nuestra página!"/>
  <div>
    <webapp-footer />
    </div>
</template>

<script>
import Home from './views/Home.vue'
import footer from './views/footer.vue'
import header from './views/header'

export default {
  name: 'App',
  components: {
  Home,
    'webapp-header':header,
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
