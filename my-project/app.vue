<script setup>
  import HeaderComponent from './HeaderComponent.vue';
  import MainComponent from './MainComponent.vue';
  import FooterComponent from './FooterComponent.vue';
</script>


<template>

  <div>

    <HeaderComponent />
    <MainComponent />
    <FooterComponent />
  </div>


</template>



<style lang="scss">

  :root {
    display: grid;
    grid-template-rows: min-content auto max-content;
    font-family: 'Montserrat', sans-serif;
  }


</style>
