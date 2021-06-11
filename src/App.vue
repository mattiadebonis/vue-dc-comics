<template>
  <div id="app">
    <!-- header della pagina -->
    <Header />
    <!-- /header della pagina -->
    
    <!-- main della pagina -->
    
    <Main />
    <!-- /main della pagina -->

    <!-- footer della pagina -->
    <Foot />
    <!-- /footer della pagina -->
  </div>
</template>

<script>
import Header from "../src/components/Header.vue";
import Main from "../src/components/Main.vue";
import Foot from "../src/components/Foot.vue";

export default {
  name: 'App',
  components:{
    Header : Header,
    Main : Main,
    Foot: Foot
    
  }
  
}
</script>

<style lang="scss">
*{
  margin:0;
  padding: 0;
  box-sizing:border-box;
}
#app {
  
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
