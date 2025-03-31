<template>

    <div class="newmain">


      <h2 class="banner">
        
        Banner

      </h2>

      <h1>Привет, Мир!</h1>

      <p>Посмотри ка на мою страничку</p>




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
  @use './style.scss' as mycss;

  .newmain {
    width: 60vw;
    height: 60vh;
    text-align: left;
  }


  .banner {
    @include mycss.magic(#138632);
    height: 5vh;
    color: white;
    display: flex;
    align-items: center;

  }

  .cards-blocks {
    display: flex;
    justify-content: left;
    gap: 10%;
  }
  
  .card {

    @include mycss.magic(#9bf8b5);
    width: 30%;
    padding-left: 5%;
    
  }

</style>