<template>
    <div id="button">

        <button> CURRENT SERIES </button>

        <div id="bottom">
            <button>Load More</button>
        </div>
    </div>

  
  
  </template>





  
  <style scoped lang="scss">

#button {
    width: 100%; 
    height: 1vh;
 
}

button {
    position: relative;
    right: 35rem;
    bottom: 2rem;
    padding: 1rem;
    background-color: #0C7CEC;
    border: 5px solid #0C7CEC;
    color: white;
    font-size: larger;
    font-weight: bold;
}
 
#bottom {
    width: 100%;
    position: relative;
    left:35rem;
    top: 80vh;

    button {
        width: 200px;
        border: 1px solid black;
        padding: 0.4rem;
        text-align: center;
        
    }
}
  
  </style>