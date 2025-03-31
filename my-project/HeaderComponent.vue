<template>

    <div class="head">
        <!-- <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,700&display=swap" rel="stylesheet"> -->

        <title>Уже 3-е ДЗ</title>
        <meta charset="utf-8">
        <meta content="width=device-width, initial-scale=1" name="viewport">
        <meta content="Cherchenko A." name="author">

    </div>

    <div class="header">
        Здраствуйте! Тут Хэдер!
    </div>

</template>

<style lang="scss">
    @use './style.scss' as mycss;

    .header {
        font-size: 30px;
        margin: 8px;
        height: 20vh;
        background: mycss.gradient(green, lightblue);
        display: flex;
        align-items: center;
        padding-left: 5%;
    }

</style>