<script setup>

    function changeText() {

    const inputText = document.getElementById("input");
    const randomTexts = [
        "Текст поменялся",
        "Вай, магия!",
        "(☞ﾟヮﾟ)☞",
        "(❁´◡`❁)"
    ];
    const randomIndex = Math.floor(Math.random() * randomTexts.length);
    inputText.textContent = randomTexts[randomIndex];
    }

</script>



<template>


    <button onclick="changeText()">
        Нажмите, чтобы поменять надпись сверху (⓿_⓿)
    </button>

    <p>
        Кнопка меняется!<br> P.s. Если у вас будут вопросы по работе или советы, вы как-то связываетесь с нами?
    </p>

</template>