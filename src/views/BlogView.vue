<script setup>
import BlogNewsItem from '../components/BlogNewsItem.vue'




</script>


<template>

        <p class="title-view">Блог</p>
        <div class="blog-view-position">
               <BlogNewsItem />
               <BlogNewsItem />
               <BlogNewsItem />
               <BlogNewsItem />
               <BlogNewsItem />
               <BlogNewsItem />
        </div>

       
</template>

<style>
        .title-view{
                color:  #4F4C4C;
                font-family: Unbounded;
                font-size: 38px;
                font-style: normal;
                font-weight: 500;
                margin: 65px 0px 55px 0px;
        }
        .blog-view-position{
                display: flex;
                flex-wrap: wrap;
                gap: 55px 29px;
        }
        .red{
                color: red;
        }
</style>
