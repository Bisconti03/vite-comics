<script >
    export default {
      name: 'DcPowerVisaCard',

    }
</script>

<template>
    <div class="card">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        <h3>DC POWER VISA</h3>
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