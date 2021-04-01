<template>
  <div>

    <div class="container text-white mt-5">

        <p>
            <NuxtLink to="/" class="d-block"><i class="fa fa-arrow-left"></i> Home</NuxtLink>
            <NuxtLink to="/postar" class="d-block"><i class="fa fa-arrow-left"></i> Artigos</NuxtLink>
            <a href="" class="d-block btn btn-success btn-postar mt-3"><i class="fa fa-paper-plane "></i> Salvar</a>
        </p>

        <div class="row mt-3">

            <div class="col-md-12">
                <label for="">Titulo do artigo</label>
                <input type="text" class="form-control mb-2 input-custom">

                <label for="" class="mt-2">Subtitulo do artigo</label>
                <input type="text" class="form-control mb-2 input-custom">

                <label for="" class="mt-2">Imagem de capa</label>
                <input type="file" class="form-control mb-1 input-custom">
               
                <no-ssr>
                  <froala id="edit" :tag="'textarea'"  ></froala>
                </no-ssr>
            </div>
            
        </div>

    </div>

  </div>
</template>

<script>

import '../assets/style/bootstrap.min.css'
import '../assets/style/root.css'
import '../assets/style/artigos.css'
import '../assets/style/perfil.css'
import '../assets/style/postar.css'


export default {
    name: 'postar',

   
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