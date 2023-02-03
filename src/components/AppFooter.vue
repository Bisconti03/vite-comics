<script >

import SignUpButton from './SignUpButton.vue';
import FooterSocials from './FooterSocials.vue';

    export default {
      name: 'AppFooter',
      components: {
        SignUpButton,
        FooterSocials,
      }

    }
</script>

<template>
  <footer>


    <div class="top-footer">
        <div class="container">
          <div class="main-divider">

            <div class="footer-lists">

              <div class="list">
                      <h2>DC COMICS</h2>
                    <ul>
                      <li><a href="#">Characters</a></li>
                      <li><a href="#">Comics</a></li>
                      <li><a href="#">Movies</a></li>
                      <li><a href="#">TV</a></li>
                      <li><a href="#">Games</a></li>
                      <li><a href="#">Videos</a></li>
                      <li><a href="#">News</a></li>
                    </ul>
                      <h2>SHOP</h2>
                    <ul>
                      <li><a href="#">Shop DC</a></li>
                      <li><a href="#">Shop DC Collectibles</a></li>
                      
                    </ul>
              </div>
              

              <div class="list">
                <h2>DC</h2>
                <ul>
                <li><a href="#">Terms OF Use</a></li>
                <li><a href="#">Privacy policy (New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent Whorkshops</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
              </ul>
              </div>

              <div class="list">
                <h2>SITES</h2>
                    <ul>
                      <li><a href="#">DC</a></li>
                      <li><a href="#">MAD Magazine</a></li>
                      <li><a href="#">Dc Kids</a></li>
                      <li><a href="#">Dc Universe</a></li>
                      <li><a href="#">DC Power Visa</a></li>
                      
                    </ul>
              </div>
              
              
          </div>

          <div class="big-logo">
              
          </div>

          </div>

         

      </div>

    </div>


    <div class="bottom-footer">
      <div class="container">
        <div class="flexer">
          <div>
            <SignUpButton/>
          </div>
          
          <div class="right-footer">

            <h2>FOLLOW US</h2>
            <FooterSocials/>
          </div>
          
        </div>

        
      </div>

    </div>
    	
  </footer>
</template>

<style lang="scss" scoped>
.top-footer {
  
    background-image: url("../assets/img/footer-bg.jpg");
    
    background-size: cover;


    .main-divider {
      display: flex;
      justify-content: space-between;


      .footer-lists {
        width: 40%;
        display: flex;
        
        flex-direction: row;

        h2 {
          color: white;
          padding: 10px 0;
        }
        .list {
          padding: 30px 0px;
          padding-right: 30px;

        }
       
        li {
          list-style: none;
          padding: 5px 0;
        }

        a {
          text-decoration: none;
          color: grey;
          
        }
      }

      


      .big-logo  {
        width: 50%;

        background-image: url("../assets/img/dc-logo-bg.png");
        background-repeat: no-repeat;
        background-position: center;
        
      }
    }
}
.bottom-footer {
  
  background-color: #303030;
  padding: 30px 0;


  .flexer {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .right-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;

    h2 {
      color: #0282f9;
      padding-right: 15px;

    }
  }
}


</style>
