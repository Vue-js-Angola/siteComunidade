<template>
    <div class="container">

        <div class="row mt-5">


            <div class="col-md-4 mt-5">
                <div class="logo">
                    <img src="/images/comunidade.jpg" class="img-fluid" alt="" srcset="">
                    
                </div>
                <h1 class="text-center text-white mt-2">Bém de volta, para continuares faça login.</h1>
            </div>

            <div class="col-md-5 mx-auto card mt-5">

                <div class="login-area">

                    <div class="row">
                        <div class="col-md-12">
                            <label for="" class="text-white mb-2">Digite seu nome</label>
                            <input type="text" class="input-custom mb-2">
                        </div>
                        <div class="col-md-12">
                            <label for="" class="text-white mb-2">Link do Github(Opcional)</label>
                            <input type="text" class="input-custom mb-2">
                        </div>

                        <div class="col-md-12">
                            <label for="" class="text-white mb-2">Digite seu endereço de email</label>
                            <input type="email" class="input-custom mb-2">
                        </div>
                        <div class="col-md-12">
                            <label for="" class="text-white mb-2">Digite a sua senha</label>
                            <input type="password" class="input-custom mb-2">
                        </div>
                    </div>

                </div>

                <a href="" class="btn btn-primary w-100 text-white mb-3"> Cadastrar</a>
                <a href="" class="btn btn-secondary w-100 text-white"><i class="fa fa-github text-white"></i> Cadastrar com Github</a>

            </div>

        </div>
       
    </div>
</template>

<script>

import '../assets/style/bootstrap.min.css'
import '../assets/style/root.css'
import '../assets/style/artigos.css'
import '../assets/style/login.css'
export default {
    name: "",
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
<style scoped>
    .card{
        width: 100%;
        max-width: 480px;
        background: rgb(32, 32, 36);
        border-radius: 5px;
        padding: 64px;
    }
    .card input{
        width: 100%;
    }
    body{
        background: rgb(18 18 20) !important;
    }
</style>