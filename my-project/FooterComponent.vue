<template>
    <footer class="footer">
        <div class="footer-container">
            <div class="footer-content">
                <div class="footer-logo">
                    <img src="/logo2.png" alt="" class="footer-logo-icon">
                </div>
                <nav class="footer-nav">
                    <a href="#" class="footer-nav-item">Реализованные проекты</a>
                    <a href="#" class="footer-nav-item">Новости</a>
                    <a href="#" class="footer-nav-item">Контакты</a>
                </nav>
                <div class="footer-contacts">
                    <div class="footer-phone">
                        <img class="footer-phone-icon" src="/telephone.png" alt="Телефон">
                        <a href="tel:+79009009090" class="footer-phone-number">+7 (900) 900-90-90</a>
                    </div>
                    <div class="footer-email">
                        <img class="footer-email-icon" src="/email.png" alt="Почта">
                        <a href="mailto:info@gmail.com">info@gmail.com</a>
                    </div>
                    <div class="footer-address">
                        <img class="footer-address-icon" src="/gps.png" alt="Адрес">
                        <address>г. Владивосток <br> ул. Выселковая 49, стр. 3</address>
                    </div>
                </div>
                <button class="footer-button">Оставить заявку</button>
            </div>
            <div class="footer-rights">
                <a class="footer-rights-item" href="#">© Загдом, 2021</a>
                <a class="footer-rights-item" href="#">Политика конфиденциальности</a>
                <a class="footer-rights-item" href="#">Пользовательское соглашение</a>
            </div>
        </div>
    </footer>
</template>

<style>
    .footer{
        background-color: #254741;
        padding-bottom: 33px;
        padding-top: 37px;
    }

    a {
        color: white;
        text-decoration: none;
    }

    .footer-container{
        display: flex;
        flex-direction: column;
        gap: 32px;
        margin: 0 60px;
    }

    .footer-content{
        display: flex;
        flex-direction: row;
        color: #ffffff;
        align-items: flex-start;
    }

    .footer-nav{
        display: flex;
        flex-direction: column;
        gap: 24px;
        font-size: 16px;
        margin-right: 122px;
        margin-left: 154px;
        padding-top: 12px;
    }

    .footer-contacts{
        display: flex;
        flex-direction: column;
        gap: 28px;
        font-size: 14px;
        font-weight: 400;
        padding-top: 11px;
    }

    .footer-contacts div{
        display: flex;
        gap: 8px;
        align-items: flex-start;
    }

    .footer-button{
        background-color: #029F59;
        color: #ffffff;
        border-radius: 10px;
        padding: 16px 30px;
        border: 0px;
        margin-left: auto;
    }

    .footer-rights{
        font-family: var(--main-font);
        font-size: 14px;
        opacity: 0.6;
        color: #ffffff;
    }
    
    .footer-rights-item:nth-child(1){
        margin-right: 215px;
    }

    .footer-rights-item:nth-child(2){
        margin-right: 99px;
    }
</style>