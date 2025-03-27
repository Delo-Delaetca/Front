<template>

    <div class="main">


      <div class="banner">

        <h2>Баннер</h2>

      </div>


      <div class="text">

        <h1>Привет, Мир!</h1>
        <p>Посмотри ка на мою страничку</p>

      </div>


      <div class="cards-blocks">

        <div class="card">

          <p>Здесь</p>

        </div>


        <div class="card">

          <p>И здесь</p>

        </div>


      </div>


    </div>


</template>
  
<style lang="scss">

  .main {
    max-width: 80vw;
    padding: 10px;
    text-align: center;
  }

  @mixin styles-of-banner($bg-color, $text-color) {
    color: $text-color;
    background-color: $bg-color;
    padding: 6px 10px;

  }

  @mixin styles-of-card($bg-color, $text-color) {
    color: $text-color;
    background-color: $bg-color;
    padding: 4px 8px;
    text-align: center;
  }

  .banner {
    @include styles-of-banner(#08771d, white);
    h2 {
      margin: 0 !important;
    }
  }

  .cards-blocks {
    display: flex;
    align-items: left;
    gap: 10px;
  }
  
  .card {
    @include styles-of-card(#9bf8b5, black);
    p {
      margin: 0 !important;
      padding: 0 !important;
    }
  }

</style>