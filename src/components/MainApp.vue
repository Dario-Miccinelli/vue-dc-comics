<template>
    <div id="AppTwo">
      
      <MainComponent/>
      <MainComponent2/>
      
  
    
    </div>
  </template>
  
  <script>
  import MainComponent from './MainComponent.vue';
  import MainComponent2 from './MainComponent2.vue';

  
  export default {
    name: 'AppTwo',
    components: {
        MainComponent,
        MainComponent2,
     
    }
  }
  </script>
  
  <style lang="scss">
  
  </style>
  