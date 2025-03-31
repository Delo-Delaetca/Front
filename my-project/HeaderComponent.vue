<template>

    <div class="header">

        <div class="navigation">

            <img class="logo" src="/logo.png" alt="logo">

            <div class="nav-items">

                <a href="#">Реализованные проекты</a>
                <a href="#">Новости</a>
                <a href="#">Контакты</a>

            </div>

        </div>


        <div class="telephone-number">

            <img class="telephone" src="/telephone.png" alt="telephone">
            <div class="number">+7 (900) 900-90-90</div>
            <button class="submit-button">Оставить заявку</button>

        </div>


    </div>

</template>



<style scoped lang="scss">

    .header {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        height: 10vh;
        align-items: center;
    }

    .navigation {
        display: flex;
        flex-direction: row;
    }

    .logo {
        inline-size: 15vw;
        margin: 2vh 3vw;
    }
    
    .nav-items {
        display: flex;
        align-items: center;
        font-size: 16px;
    }
    
    a {
        margin: 2vh 1vw;
        font-family: Open Sans, sans-serif;
        color: #666666;
        text-decoration: none;
    }
    
    .telephone-number {
        display: flex;
        flex-direction: row;
        align-items: center;
        font-family: Monserrat, sans-serif ;
        font-size: 16px;
        color: #666666;

    }
    
    .number {
        margin-left: 1vw;
    }

    .submit-button {
        margin: 2vw;
        width: 15vw;
        height: 6vh;
        border-radius: 10px;
        padding: 16px 40px;
        background-color: #029F59;
        border: 0;
        color: white;
        display: flex;
        align-items: center;
        justify-content: center;
    }

</style>