<script >
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooter from './components/AppFooter.vue';


    export default {
      name: 'App',
      components: {
        AppHeader,
        AppMain,
        AppFooter
      }

    }
</script>

<template >
  <div class="container">
    <AppHeader />
  </div>
  
    <AppMain />

    <AppFooter />
  
  
</template>

<style lang="scss" >
@use "./styles/main.scss";



</style>
