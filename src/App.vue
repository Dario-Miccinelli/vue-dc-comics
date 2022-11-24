<template>
  <div id="app">
    
    <HeaderApp/>
    <JumboTron/>
    <MainApp/>
    <FooterApp/>

  
  </div>
</template>

<script>
import HeaderApp from './components/HeaderApp.vue';
import JumboTron from './components/JumboTron.vue';
import MainApp from './components/MainApp.vue';
import FooterApp from './components/FooterApp.vue';

export default {
  name: 'App',
  components: {
    HeaderApp,
    JumboTron,
    MainApp,
    FooterApp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 1rem;

}


body {
margin: 0;
}


</style>
