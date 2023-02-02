<script >
    export default {
      name: 'SubscriptionCard',

    }
</script>

<template>
    <div class="card">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <h3>SUBSCRIPTION</h3>
    </div>
  

</template>

<style lang="scss" scoped >

.card {
    display: flex;
    align-items: center;
    
    
    width: calc((100% / 5) - 15px);
    padding: 30px 15px;

    img {
        width: 60px;
        
    }

    h3 {
        color: white;
        padding-left: 20px;
        
    }
}

</style>