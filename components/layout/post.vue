<template>
  
    <div>

        <a href="">
            <div class="post-img">
                <img :src="`/images/${imgPost}`" alt="dd">
            </div>
               
            <div class="post-title mt-2">
                <span>O que é e como aprender Vue.js</span>
            </div>
            <div class="post-data">
                Quarta-feira, 24 de março de 2021
            </div>
        </a>

    </div>
    
</template>

<script>
export default {
    name: 'post',
    props: ['imgPost'],
    
}
</script>

<style>

</style>