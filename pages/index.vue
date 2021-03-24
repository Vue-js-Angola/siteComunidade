<template>
  <div>
   

    <header-menu></header-menu>
    <banner-menu></banner-menu>

      
  </div>
</template>

<script>
import headerMenu from '../components/layout/header.vue'
import { Carousel, Slide } from 'vue-carousel';
import bannerMenu from '../components/layout/banner.vue'
export default {

  name: 'index',
  components: {headerMenu, bannerMenu},

  created(){
    console.log(this.$vueCarousel)
  }
}
</script>

<style>

</style>
