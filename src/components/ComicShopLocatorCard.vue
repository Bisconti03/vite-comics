<script >
    export default {
      name: 'ComicShopLocatorCard',

    }
</script>

<template>
    <div class="card">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <h3>COMIC SHOP LOCATOR</h3>
    </div>
  

</template>

<style lang="scss" scoped >

.card {
    display: flex;
    align-items: center;
    
    
    width: calc((100% / 5) - 15px);
    padding: 30px 15px;

    img {
        width: 40px;
        
    }

    h3 {
        color: white;
        
        
    }
}

</style>