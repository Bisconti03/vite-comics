<script >
    export default {
      name: 'DcMerchandiseCard',

    }
</script>

<template>
    <div class="card">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <h3>DC MERCHANDISE </h3>
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