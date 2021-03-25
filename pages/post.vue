<template>
  <div>

    <div class="container text-white mt-5">

        <p>
            <NuxtLink to="/artigos"><i class="fa fa-arrow-left"></i> Artigos</NuxtLink>
        </p>

        <div class="row mt-5">

            <div class="col-md-6 mx-auto mt-5">
                <h1 class="post-title">Trabalhando com Mixins no Vue.js</h1>
             
                <div class="author-info-post">
                    <img src="https://avatars.githubusercontent.com/u/39365797?s=460&u=4ebebc0bce1839222a2ce180b0b4aa0e13d45b1a&v=4" alt="" class="img-fluid">
                    <span>
                        <a href="">Edson2001</a>
                    </span>
                    <div class="data">
                        22-03-2021
                    </div>
                    <div class="detalhe ">
                        <a href="" title="Partilhar"><i class="fa fa-paper-plane"></i></a>
                        <a href="" title=""><i class="fa fa-trophy"></i> 2K</a>
                    </div>
                </div>
                  
                
                <h5 class="post-subtitle">
                    Mixins são uma forma flexível de distribuir funcionalidade reutilizável em diversos componentes Vue.
                </h5>
                <div class="post-img">
                    <img src="/images/post3.png" alt="" class="img-fluid w-100">
                </div>
                <div class="post-text mt-3 mb-2">
                    Dentro dos meus trabalhos com Vue, eu venho adquirindo muita experiência no 
                    desenvolvimento de componentes e reaproveitamento dos mesmos nas aplicações, 
                    ganhando assim, agilidade, tempo, recursos, entre outros. 
                    E nos últimos projetos eu vinha percebendo que alguns dos meus componentes tinham códigos
                     bastante semelhantes, entre os quais, alguns methods, computed properties.
                </div>

                <div class="post-text mt-3 mb-2">
                    Dentro dos meus trabalhos com Vue, eu venho adquirindo muita experiência no 
                    desenvolvimento de componentes e reaproveitamento dos mesmos nas aplicações, 
                    ganhando assim, agilidade, tempo, recursos, entre outros. 
                    E nos últimos projetos eu vinha percebendo que alguns dos meus componentes tinham códigos
                     bastante semelhantes, entre os quais, alguns methods, computed properties.
                </div>

                <div class="post-text mt-3 mb-2">
                    Dentro dos meus trabalhos com Vue, eu venho adquirindo muita experiência no 
                    desenvolvimento de componentes e reaproveitamento dos mesmos nas aplicações, 
                    ganhando assim, agilidade, tempo, recursos, entre outros. 
                    E nos últimos projetos eu vinha percebendo que alguns dos meus componentes tinham códigos
                     bastante semelhantes, entre os quais, alguns methods, computed properties.
                </div>
                <img src="/images/1_1dJ50HokwxdxG_2FEwVvkw.png" alt="" class="img-fluid">

                <div class="post-author-info mt-3">

                </div>
            </div>

            

        </div>

        

    </div>

    <vue-footer></vue-footer>

  </div>
</template>

<script>
import VueFooter from '../components/layout/vueFooter.vue'
import '../assets/style/bootstrap.min.css'
import '../assets/style/root.css'
import '../assets/style/artigos.css'

export default {
    name: 'artigos',
    components: {VueFooter},
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