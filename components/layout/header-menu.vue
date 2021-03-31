<template>
  
    <div>

        <header id="header">
            <div class="inner">
                <div class="logo">
                    <a href="/" >Vue.js Angola</a>
                </div>
                <nav id="nav">
                    <ul class="inner">
                          
                        <li><NuxtLink to="/">Home</NuxtLink></li>
                        <li><a href="#membro">Membros</a></li>
                        <li><NuxtLink to="/artigos">Artigos</NuxtLink></li>
                        <li><NuxtLink to="/" class="btn btn-primary">Conta</NuxtLink></li>
                        <li v-if="page == 'artigos'"><NuxtLink to="/artigos">Postar</NuxtLink></li>
                    </ul>
                </nav>
            </div>
        </header>
    </div>

</template>

<script>
import '../../assets/style/root.css'
import '../../assets/style/header.css'
export default {
    name: 'header-menu',
    data(){
        return{
            page: this.$route.name
        }
    },
    created(){
        console.log(this.page)
    }
}
</script>

<style>

</style>