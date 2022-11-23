<template>
    <div id="Footer">
        <div id="FooterLeft">
            <ul class="column">

                <h5>DC COMICS</h5>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>

                <h5>SHOP</h5>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>

            </ul>
            <ul class="column">

                <h5>DC </h5>
                <li>Terms Of Use</li>
                <li>Privacy polici</li>
                <li>Ad choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscription</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>

            </ul>
            <ul class="column">

                <h5>SITES</h5>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
                
            </ul>
        </div>

        <div id="Image">
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>



</template>
  

  
<style scoped lang="scss">
* {
    display: flex;
}

.column {
    display: flex;
    flex-direction: column;
    
    align-items: center;


}

h2 {
    margin: auto;
}

#Footer {
    background-image: url(../assets/img/footer-bg.jpg);

    width: 100%;
    height: 40vh;
    color: white;
    

}

#FooterLeft {
    width: 50%;
}

#Image>img {
    height: 100%;
    width: 100%;
    margin-left: 90%;
    
    

}

ul {
    
    width: 20%;
    padding: 1rem;
    

    li {
        color: lightslategray;
        font-size: smaller;
    }
}
</style>