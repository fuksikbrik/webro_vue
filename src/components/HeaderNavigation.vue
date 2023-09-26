<script setup>

</script>

<template>
    <nav class="navigation-link">
       <router-link class="link" to="/about">О нас</router-link>
       <router-link class="link" to="/contact">Контакты</router-link>
       <router-link class="link" to="/blog">Блог</router-link>
    </nav>
    
</template>

<style>
    .navigation-link{
        display: flex;
        justify-content: space-between;
        gap: 48px;
    }
    .link{
        text-decoration: none;
        color: black;
        color: #4F4C4C;
        font-family: Unbounded;
        font-size: 14px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;        
    }
</style>