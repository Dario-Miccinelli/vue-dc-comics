<template>
  <div id="header">
    <div class="between">
      <img src="../assets/img/dc-logo.png" alt="Logo header">
      <div>
        <ul>
          <li>CHARACTERS</li>
          <li class="comics">COMICS</li>
          <li>MOVIES</li>
          <li>TV</li>
          <li>GAMES</li>
          <li>COLLECTIBLES</li>
          <li>VIDEOS</li>
          <li>FANS</li>
          <li>NEWS</li>
          <li>SHOP</li>
        </ul>
      </div>
    </div>
    </div>
  
  </template>
  

  
  <style scoped lang="scss">
  *{
    display: flex;
   
  }
  .between{
    justify-content: space-around;
    width: 90%;
    margin: auto;
  }

 
//   nesting ul li scss

  ul{
    align-self: center;
    font-weight: 600;
    li{
    padding: 0rem  .5rem;
  }}

 

  .comics {
    color: blue;
    font-weight: 600;
    border-bottom: 5px solid blue;
    
  }
  </style>