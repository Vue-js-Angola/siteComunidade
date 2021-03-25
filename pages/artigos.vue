<template>
  <div>
      <header-menu></header-menu>
        <div class="banner-artigos">
            <div class="container">
                <div class="row">
                    <div class="col-md-6 mx-auto">
                        <div class="banner-img">
                            <img src="/images/1200px-Vue.js_Logo_2.svg.png" class="img-fluid" alt="">
                        </div>
                        <h2 class="text-center">Vue.js Angola</h2>
                        <p class="text-center">Artigos da comunidade</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="container text-white mt-5">

            <h6  class="text-center">Todos os artigos, são feitos pelos membros da comunidade</h6>

            <div class="row mt-5">

                <div class="col-md-7 mx-auto">
                    <NuxtLink to="/post">
                        <article>
                            <div class="artigo-title">
                                <h5>Construindo sua aplicação com Styled Components no Vue.js</h5>
                            </div>
                            <div class="artigo-preview">
                                O Styled-Components é uma biblioteca muito popular dentro da comunidade 
                                React e do React Native, e agora você poderá utilizá-la no Vue.js. »
                            </div>
                            <div class="artigo-info">
                                <div class="author-info">
                                    <img src="https://avatars.githubusercontent.com/u/39365797?s=460&u=4ebebc0bce1839222a2ce180b0b4aa0e13d45b1a&v=4" alt="" class="img-fluid">
                                    <span>Edson2001</span>
                                </div>
                                <div class="data">
                                    22-03-2021
                                </div>  
                            </div>
                        </article>
                    </NuxtLink>
                </div>

                <div class="col-md-7 mx-auto">
                    <a href="">
                        <article>
                            <div class="artigo-title">
                                <h5>Construindo sua aplicação com Styled Components no Vue.js</h5>
                            </div>
                            <div class="artigo-preview">
                                O Styled-Components é uma biblioteca muito popular dentro da comunidade 
                                React e do React Native, e agora você poderá utilizá-la no Vue.js. »
                            </div>
                            <div class="artigo-info">
                                <div class="author-info">
                                    <img src="https://avatars.githubusercontent.com/u/39365797?s=460&u=4ebebc0bce1839222a2ce180b0b4aa0e13d45b1a&v=4" alt="" class="img-fluid">
                                    <span>Edson2001</span>
                                </div>
                                <div class="data">
                                    22-03-2021
                                </div>  
                            </div>
                        </article>
                    </a>
                </div>

                <div class="col-md-7 mx-auto">
                    <a href="">
                        <article>
                            <div class="artigo-title">
                                <h5>Construindo sua aplicação com Styled Components no Vue.js</h5>
                            </div>
                            <div class="artigo-preview">
                                O Styled-Components é uma biblioteca muito popular dentro da comunidade 
                                React e do React Native, e agora você poderá utilizá-la no Vue.js. »
                            </div>
                            <div class="artigo-info">
                                <div class="author-info">
                                    <img src="https://avatars.githubusercontent.com/u/39365797?s=460&u=4ebebc0bce1839222a2ce180b0b4aa0e13d45b1a&v=4" alt="" class="img-fluid">
                                    <span>Edson2001</span>
                                </div>
                                <div class="data">
                                    22-03-2021
                                </div>  
                            </div>
                        </article>
                    </a>
                </div>

            </div>

        </div>

      <vue-footer></vue-footer>
  </div>
</template>

<script>
import headerMenu from '../components/layout/header-menu.vue'
import VueFooter from '../components/layout/vueFooter.vue'
import '../assets/style/bootstrap.min.css'
import '../assets/style/root.css'
import '../assets/style/artigos.css'

export default {
    name: 'artigos',
    components: {headerMenu, VueFooter},
    head: {

    title: 'Vue.js Angola',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'Em breve site da comunidade vue.js Angola',
      },
     
    ],

    link: [
      {
        rel: 'stylesheet',
        href: 'https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css'
      },
     
    ]
  },
}
</script>

<style>

</style>