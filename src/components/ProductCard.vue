<template>
    
    <div class="card">
        

  
      <img :src="dettagliProdotto.thumb"   alt="">
      <h4>{{ dettagliProdotto.series }}</h4>
      
    </div>

  </template>
  
  <script>
    export default {
      name: 'ProdottoCard',
      props: {
        dettagliProdotto: Object
      }
    }
  </script>
  
  <style lang="scss" scoped>
  
  .card{    
    color: white;
    width: calc(100% / 6);


  }

  



  </style>