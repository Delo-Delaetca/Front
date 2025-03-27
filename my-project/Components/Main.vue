<script setup>

    import Button from './Button.vue';

</script>



<template>

    <div class="body">


        <div class="content">

            <div class="left">

                <p class="textcenter">
                    Тут будет список опций!
                </p>

                <ul>
                    <li>
                        Я получил балл!
                    </li>

                    <li>
                        Я получил балл?
                    </li>

                    <li>
                        Я получил балл!?
                    </li>

                </ul>

                <div class="banner">

                    <span>Баннер</span>

                </div>

            </div>

            <div class="center">

                <div class="centerblock">

                    <h2>
                        Главное на странице?
                    </h2>

                    <p id="input">Тут будет меняться надпись!</p>

                    <br>

                    <Button />

                </div>

            </div>

            <div class="right">

                <p>
                    Что-то вроде должно быть, но оно потерялось ༼ つ ◕_◕ ༽つ
                </p>

                <br>
                
                <img class="Cat" src="images/cat.jpg" alt="Кот">

                <br>

                <p class="montserrat-MyCss">
                    Нашлось! o(*￣▽￣*)ブ
                </p>

            </div>

        </div>
        


    </div>

</template>



<style lang="scss">

    :root {
        --font-primary: 'Montserrat', sans-serif;
        --font-secondary: 'Open Sans', sans-serif;
    }

    body {
        margin: 0 !important;
        font-family: var(--font-primary);
    }

    p {
        
        font-family: var(--font-secondary);
    }


    .content {
        margin-top: 15px;
        display: flex;
        justify-content: space-between;
        height: 70vh;
    }

    .left {
        background-color: rgb(23, 175, 23);
        width: 20vw;
    }

    .textcenter {
        text-align: center;
    }

    .center {
        background-color: yellow;
        width: 50vw;
        text-align: center;
    }

    .centerblock {
        position: relative;
        top: 20%;
    }

    .right {
        background-color: rgb(20, 188, 20);
        width: 20vw;
        text-align: center;
        padding: 0 10px 0 10px;
    }

    .Cat {
        width: 100%;
    }

    /* Так было сразу, когда я копировал с гугла. Я решил на переменную тоже заменить фонт-фэмили. Хотя я ссылку гугла посмотрел, там уже 
    напиман какой фонт долен быть, разве нет? Там и 700, и италик, и монстеррат указаны уже. Это я не допонял.*/
    /* .montserrat-MyCss {
        font-family: "Montserrat", sans-serif;
        font-optical-sizing: auto;
        font-weight: 700;
        font-style: italic;
    } */

    .montserrat-MyCss {
        font-family: var(--font-primary);
        font-optical-sizing: auto;
        font-weight: 700;
        font-style: italic;
    }


</style>