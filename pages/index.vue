<template>
  <div>
   

    <header-menu></header-menu>
    <banner-menu></banner-menu>

    <div class="container mt">

        <div class="row mt-5">

          <div class="col-md-4 mt-3">

            <img src="/images/1200px-Vue.js_Logo_2.svg.png" alt="" class="img-fluid">

          </div>

          <div class="col-4 text-white mt-3">
            <h3>Quem somos?</h3>
            <p>
              A Vue.js Angola, é uma comunidade angolana focada no framework progressivo vue.js.
            </p>
            <p>
              A ideia ajudar aqueles que queiram entrar no mundo do vue.js, com projectos, ideias
              construtivas e muito mas.
            </p>
            <p>
              <a href=""><i class="fa fa-github"></i></a>
              <a href=""><i class="fa fa-facebook"></i></a>
            </p>
          </div>

          <div class="col-md-4 text-white mt-3">

            <h3>Como ser membro?</h3>
            <p>
              A Vue.js Angola, é uma comunidade angolana aberta para qualquer desenvolvedor que queira 
              fazer parte deste projeto.
            </p>
            <p>
              Claro, seguindo as regras, respeitar os outros membros.
            </p>
            <p><a href=""><i class="fa fa-github"></i></a> Faça parte da comunidade, entrado no nosso github.</p>

          </div>

        </div>

        <h3 class="text-white mt-5">Membros da comunidade</h3>
        <div class="row  text-white" id="membro">

          <div class="col-md-4  col-sm-6">
            <a target="_blank" href="https://github.com/edson2001">
              <membro :user_name="'edson2001'"></membro>
            </a>
          </div>

          <div class="col-md-4  col-sm-6">
            <a target="_blank" href="https://github.com/MartinsSilva">
              <membro :user_name="'MartinsSilva'"></membro>
            </a>
          </div>

          <div class="col-md-4  col-sm-6">
            <a target="_blank" href="https://github.com/Lazaro-Inacio">
              <membro :user_name="'Lazaro-Inacio'"></membro>
            </a>
          </div>

          <div class="col-md-4  col-sm-6">
            <a target="_blank" href="https://github.com/edgarsingui">
              <membro :user_name="'edgarsingui'"></membro>
            </a>
          </div>

          <div class="col-md-4  col-sm-6">
            <a target="_blank" href="https://github.com/MartinDala">
              <membro :user_name="'MartinDala'"></membro>
            </a>
          </div>

          <div class="col-md-4  col-sm-6">
            <a target="_blank" href="https://github.com/gentildpinto">
              <membro :user_name="'gentildpinto'"></membro>
            </a>
          </div>

        </div>

      <h3 class="text-white mt-5">Últimos artigos da comunidade</h3>
      <p>
        <a href="">Fique por dentro dos nossos últimos artigos! Ver mais &raquo;</a>
      </p>
      <div class="row" >

        <div class="col-md-3 ">
          <post-item class="post-item posts" :imgPost="'post.png'"></post-item>
        </div>

        <div class="col-md-3 ">
          <post-item class="post-item posts" :imgPost="'post2.png'"></post-item>
        </div>

        <div class="col-md-3 ">
          <post-item class="post-item posts" :imgPost="'post3.png'"></post-item>
        </div>

        <div class="col-md-3 ">
          <post-item class="post-item posts" :imgPost="'post4.png'"></post-item>
        </div>
        
      </div>

      <div class="row mt-5">
        <div class="alert bg-dark text-white">
          <h4>Ajude a comunidade a crescer com projectos, artigos e muito mas.</h4>
          <ul>
            <li>
              
              <a href=""><i class="fa fa-home"></i> Criar artigos, com a sua ajuda vamos criar artigos, ajudando outros membros.</a>
            </li>
            <li>
              <a href=""><i class="fa fa-book"></i> Criar projectos, com a sua ajuda vamos criar projectos, com estes projectos 
              vais ajudar a comunidade a crescer assim como ajudar outros membros.</a>
            </li>

            <li>
              <a href=""><i class="fa fa-users"></i> Eventos, em breve termos alguns eventos, com o objectivo de crescer a comunidade,
                qualquer membro pode participar, com ideias, projectos e muito mas.
              </a>
            </li>
          </ul>
        </div>
      </div>

    </div>

    <vue-footer></vue-footer>
      
  </div>
</template>

<script>

import headerMenu from '../components/layout/header-menu.vue'
import bannerMenu from '../components/layout/banner.vue'
import postItem from '../components/layout/post.vue'
import '../assets/style/bootstrap.min.css'
import '../assets/style/root.css'
import Membro from '../components/layout/membro.vue'
import VueFooter from '../components/layout/vueFooter.vue'
export default {

  name: 'index',
  data(){
    return{
      
    }
  },
  components: {headerMenu, bannerMenu, postItem, Membro, VueFooter},

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
