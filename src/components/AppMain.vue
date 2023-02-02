<script >
    export default {
      name: 'AppMain',

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

        </div>

    </div>
  </main>
</template>

<style lang="scss" scoped>

main {
    background-color: #1c1c1c;

    

    h1 {
        color: white;
    }
}


.top-main {
    height: 15vh;
    display: flex;
    align-items: center;
}


.bottom-main {
    height: 55vh;
    background-image: url("../assets/img/footer-bg.jpg");
    
    background-size: cover;
}

</style>
