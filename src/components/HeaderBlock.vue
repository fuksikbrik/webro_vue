<script setup>
import HeaderBlockOne from './HeaderBlockOne.vue' 
import HeaderBlockTwo from './HeaderBlockTwo.vue'
</script>

<template>
    <div class="header">
        <HeaderBlockOne></HeaderBlockOne>
        <HeaderBlockTwo></HeaderBlockTwo>
    </div>
    
</template>

<style>
    .header{
        display: flex;
        flex-direction: column;
        width: 100%;
    }
</style>