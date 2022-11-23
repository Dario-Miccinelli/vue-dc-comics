<template>
    <div id="Footer">
        <div id="FooterWidth80">
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
          
        </div>
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
    background-position: center;
    


    width: 100%;
    height: 40vh;
    color: white;
    

}

#FooterLeft {
    width: 50%;
}

#Image {
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    width: 70%;
    height: 370px;
    margin-left: 25%;

  
  
} 

ul {
    
    width: 40%;
    padding-left: 3rem;
    padding-top: 2rem;
    

    li {
        color: lightslategray;
        font-size: smaller;
    }
}

#FooterWidth80 {
    width: 80%;
    margin: auto;
}

  </style>