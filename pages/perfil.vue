<template>
  <div>

    <div class="container text-white mt-5">

        <p>
            <NuxtLink to="/" class="d-block"><i class="fa fa-arrow-left"></i> Home</NuxtLink>
            <NuxtLink to="/postar"><i class="fa fa-arrow-left"></i> Publicar</NuxtLink>
        </p>

        <div class="row mt-5">

            <div class="col-md-8 mx-auto">

                <div class="user">

                    <div class="user-img">
                        <img src="/images/post4.png" class="img-fluid" alt="">
                    </div>

                    <div class="info-user">
                        <h5>Edson Dos Santos</h5>
                        <p class="description">This repository is for projects by the vuejs Angola community</p>
                        <p>
                            Artigos: <b>4</b>
                        </p>
                    </div>

                </div>

                <h5 class="mt-5">Últimos artigos publicados!</h5>

                <div class="row mt-3" >

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
                    
            </div>
            
        </div>

        

       

    </div>

    

  </div>
</template>

<script>
import postItem from '../components/layout/post.vue'
import '../assets/style/bootstrap.min.css'
import '../assets/style/root.css'
import '../assets/style/artigos.css'
import '../assets/style/perfil.css'


export default {
    name: 'perfil',
    components: {postItem},
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