<script>

</script>

<template>
        <div class="news-item">
            <img src="../assets/image/png.png" alt="">
            <p class="title">Новая новость </p>
            <p class="sub-title">
                Позиционирование: нежность и забота о себе.
                 Игрушки - это друг девушки, благодаря которому
                  она может узнать своё тело, узнать себя и узнать
                   что ей нравится.
            </p>
            <div class="next-and-arrow">
                <p>Читать дальше </p>
                <svg xmlns="http://www.w3.org/2000/svg" width="21" height="16" viewBox="0 0 21 16" fill="none">
                    <path d="M20.7071 8.70711C21.0976 8.31658 21.0976 7.68342 20.7071 7.29289L14.3431 0.928932C13.9526 0.538408 13.3195 0.538408 12.9289 0.928932C12.5384 1.31946 12.5384 1.95262 12.9289 2.34315L18.5858 8L12.9289 13.6569C12.5384 14.0474 12.5384 14.6805 12.9289 15.0711C13.3195 15.4616 13.9526 15.4616 14.3431 15.0711L20.7071 8.70711ZM0 9H20V7H0V9Z" fill="#7761B6"/>
                </svg>
            </div>

        </div>
</template>

<style>
    .news-item{
        max-width: 367px;
    }
    .title{
        color:  #4F4C4C;
        font-family: Unbounded;
        font-size: 20px;
        font-style: normal;
        font-weight: 500;
    }
    .title:hover{
        color:  #7761B6;
        text-decoration-line: underline;
    }
    .sub-title{
        color:  #4F4C4C;
        font-family: Unbounded;
        font-size: 12px;
        font-style: normal;
        font-weight: 300;
        letter-spacing: 0.6px;
    }
    .next-and-arrow{
        display: flex;
        justify-content: start;
        gap: 20px;
        align-items: center;
        transition: .4s;
    }
    .next-and-arrow > p{
        color:  #7761B6;
        font-family: Unbounded;
        font-size: 14px;
        font-style: normal;
        font-weight: 400;
    }
    .next-and-arrow:hover > p {
        text-decoration: underline;
    }
    .next-and-arrow:hover{
        gap: 35px;
    }
</style>