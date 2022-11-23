<template>
    <div id="FooterFinale">
        <div id="w-80">
            <div id="left">
                <button>SIGN-UP NOW!</button>
            </div>
            <div id="right">

                <H2>FOLLOW US</H2>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">

            </div>
        </div>
    </div>

</template>
  

  
<style scoped lang="scss">
* {
    display: flex;

}
#w-80 {
    width: 80%;
    margin: auto;
    justify-content: center;
    justify-content: space-between;
    ;
   
}


h2 {
    color: blue;
    padding: 1rem;
}
#right img {
    width: 50px;
    height: 50px;
    padding: 1rem;
    
}




button {
    border: 1px solid blue;
    padding: 2rem;
    background-color: #2f2f2f;
    color: white;
    margin-top: 1rem;
    
}

#FooterFinale {
    background-color: #2f2f2f;
    height: 15vh;
    color: white;
    margin: 0;

}
</style>