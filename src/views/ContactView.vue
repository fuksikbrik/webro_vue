<script setup>

</script>

<template>
    <div class="contact">
        <div class="contact-left">
            <p>Если вы заинтересованы в любом виде сотрудничества - просто свяжитесь с нами по почте <a href="">info@we-bro.com</a> или через форму обратной связи </p>
            <input class="input" type="text" placeholder="Ваше имя">
            <input class="input" type="text" placeholder="E-mail">
            <input class="input" type="text" placeholder="Телефон">
            <textarea class="textarea" name="" id="" cols="30" rows="10" placeholder="Ваш вопрос"></textarea>
            <div class="checkbox-and-label">
                <input class="checkbox" type="checkbox">
                <label for="">Нажимая кнопку “Отправить” я соглашаюсь с Политикой конфиденциальности сайта</label>
            </div>
        </div>
        <div>
            <img src="../assets/image/contact-image.svg" alt="">
        </div>
    </div>
</template>

<style>
    .contact{
        display: flex;
        justify-content: space-between;
    }
    .contact-left{
        display: flex;
        flex-direction: column;
        align-items: start;
        width: 70%;
        gap: 20px;
    }
    .contact-left >  input,textarea{
        width: 100%;
    }
    .input{
        border-radius: 50px;
        border:1px solid #9B9B9B;
        padding: 14px 0px 14px 17px;
        font-family: Unbounded;
        font-size: 12px;
        font-style: normal;
        font-weight: 300;
    }
    .textarea{
        padding:14px 0px 0px 17px ;
        border-radius: 20px;
        color: var(--Light-Gray, #C3C3C3);
        font-family: Unbounded;
        font-size: 12px;
        font-style: normal;
        font-weight: 300;
    }
</style>