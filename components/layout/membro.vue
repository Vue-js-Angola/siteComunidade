<template>
  <div>

    <div class="membro-card">
        <div class="membro-img">
        <img :src="user.avatar_url" alt="">
        </div>
        <div class="membro-descricao">
        <span class="text-white">{{user.name}}</span>
        <span>{{user.bio}}</span>
        <span class="text-white">{{user.location}}</span>
        </div>
    </div>

  </div>
</template>

<script>
export default {

    name: 'membro',
    data(){

        return{
            user: ''
        }

    },
    props: ['user_name'],
        created(){
        this.asyncData()
    },

    methods:{
     asyncData() {
      this.$axios.get('https://api.github.com/users/'+this.user_name).then(response=>{
        this.user = response.data
      })
      
    }
  }

}
</script>

<style>

</style>