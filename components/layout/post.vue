<template>
  
    <div>

        <a href="">
            <div class="post-img">
                <img :src="`@/assets/images/comunidade.jpg`" alt="dd">
            </div>
                {{imgPost}}
            <div class="post-title">
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
    created(){
        console.log(this.imgPost)
    }
}
</script>

<style>

</style>