<template>
  <div>
   

    <header-menu></header-menu>
    <banner-menu></banner-menu>

    <div class="container mt">
      <h3>Últimos artigos da comunidade</h3>
      <p>Fique por dentro dos nossos últimos artigos!</p>
      <div class="posts inner">
        <post-item class="post-item" :imgPost="'post.png'"></post-item>
        <post-item class="post-item" :imgPost="'post2.png'"></post-item>
        <post-item class="post-item" :imgPost="'post3.png'"></post-item>
        <post-item class="post-item" :imgPost="'post4.png'"></post-item>
      </div>

    </div>

      
  </div>
</template>

<script>
import headerMenu from '../components/layout/header-menu.vue'
import bannerMenu from '../components/layout/banner.vue'
import postItem from '../components/layout/post.vue'
import '../assets/style/root.css'
export default {

  name: 'index',
  components: {headerMenu, bannerMenu, postItem},

  created(){
    
  }
}
</script>

<style>

</style>
