<template>

    <div class="footer">

        <h2>Тут Футер!</h2>

    </div> 

</template>

<style lang="scss">
    @use './style.scss' as mycss;

    .footer {
        background: mycss.gradient(blue, grey);
        position: fixed;
        bottom: 0;
        height: 10vh;
        width: 100%;
        display: flex;
        align-items: center;
    }

    h2 {
        padding-left: 5%;

    }
 
</style>