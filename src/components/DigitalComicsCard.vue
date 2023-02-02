<script >
    export default {
      name: 'DigitalComicsCard',

    }
</script>

<template>
    <div class="card">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <h3>DIGITAL COMICS</h3>
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