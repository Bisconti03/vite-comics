<script >
import DcLogo from './DcLogo.vue';


    export default {
      name: 'AppHeader',
      components: {
        DcLogo
      }

    }
</script>

<template>
  <header>
      <div>
        <DcLogo/>
      </div>

      <div class="list">
        <ul>
            <li>
                <a href="#">CHARACTERS</a>
            </li>
            <li class="active" >
                <a  href="#">COMICS</a>
            </li>
            <li>
                <a href="#">MOVIES</a>
            </li>
            <li>
                <a href="#">TV</a>
            </li>
            <li>
                <a href="#">GAMES</a>
            </li>
            <li>
                <a href="#">COLLECTIBLES</a>
            </li>
            <li>
                <a href="#">VIDEOS</a>
            </li>
            <li>
                <a href="#">FANS</a>
            </li>
            <li>
                <a href="#">NEWS</a>
            </li>
            <li>
                <a href="#">SHOP</a>
            </li>
        </ul>
      </div>
        
    
    
  </header>
</template>

<style lang="scss" scoped >

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: row;
    


}

ul {
    display: flex;
    list-style: none;

     
        li {
            padding: 60px 15px;
            
        }


         a {
            text-decoration: none;
            color: black;
            font-weight: bold;
            
        }
    

    

   
   

}


.active {
    
    border-bottom: 2px solid #0282f9;

    a {
        color: #0282f9;
    }
    
}


</style>
