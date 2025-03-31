<script setup>

  import HeaderComponent from './HeaderComponent.vue';
  import FooterComponent from './FooterComponent.vue';
  import Banner from './Banner.vue';


</script>


<template>

  <div>

    <HeaderComponent />


    <div class="main">

      <Banner /> 

    </div>
    
    <FooterComponent />

  </div>

</template>



<style lang="scss">
  :root {
    font-family: Montserrat, sans-serif;
    font-size: 3vmin;
    }

  .main {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    height: 60vh;
  }

</style>
