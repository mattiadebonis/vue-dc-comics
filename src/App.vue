<template>
  <div id="app">
    <!-- header della pagina -->
    <Header />
    <!-- /header della pagina -->
    
    <!-- main della pagina -->
    <main>Main della pagina</main>
    <!-- /main della pagina -->

    <!-- footer della pagina -->
    <footer>Footer della pagina</footer>
    <!-- /footer della pagina -->
  </div>
</template>

<script>
import Header from "../src/components/Header.vue";
export default {
  name: 'App',
  components:{
    Header : Header
    
    
  }
  
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
