<script >
import DigitalComicsCard from './DigitalComicsCard.vue';
import DcMerchandiseCard from './DcMerchandiseCard.vue';
import SubscriptionCard from './SubscriptionCard.vue';
import ComicShopLocatorCard from './ComicShopLocatorCard.vue';
import DcPowerVisaCard from './DcPowerVisaCard.vue';

    export default {
      name: 'AppMain',
      components: {
        DigitalComicsCard,
        DcMerchandiseCard,
        SubscriptionCard,
        ComicShopLocatorCard,
        DcPowerVisaCard,

      }

    }
</script>

<template>
  <main>
    
    <div class="container">

        <div class="top-main">
            <h1> Content goes here  </h1>

        </div>


    </div>

    <div class="bottom-main">

        <div class="container">
            <div class="cards">
                <DigitalComicsCard/>
                <DcMerchandiseCard/>
                <SubscriptionCard/>
                <ComicShopLocatorCard/>
                <DcPowerVisaCard/>
            </div>
         
        </div>

    </div>
  </main>
</template>

<style lang="scss" scoped>

main {
    background-color: #1c1c1c;

    

    h1 {
        color: white;
        padding: 40px 0;
    }
}


.top-main {
    
    display: flex;
    align-items: center;
}


.bottom-main {
    
    background-color: #0282f9;

   
    
}

.cards {
    display: flex;
    justify-content: space-between;
    
    
}

</style>
