<template>
  <div>
   

    <header-menu></header-menu>
    <banner-menu></banner-menu>

  </div>
</template>

<script>
import headerMenu from '../components/layout/header.vue'

import bannerMenu from '../components/layout/banner.vue'
export default {

  name: 'index',
  components: {headerMenu, bannerMenu}

}
</script>

<style>

</style>
