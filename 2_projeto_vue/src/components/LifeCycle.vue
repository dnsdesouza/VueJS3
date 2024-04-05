<<<<<<< HEAD
<template>
    <h1>
        Meu nome é: {{ nome }}
    </h1>
</template>

<script>
export default {
    name: 'LyfeCycle',
    data(){
        return{
            nome:'Ainda não sei'
        }
    },
    created() {
        setTimeout(() =>{
            this.nome ="Matheus"
        }, 1000)
       
    },
    mounted(){
        setTimeout(() =>{
            this.nome ="Pedro"
        }, 2000)
    }
}
</script>
=======
<template>
  <h1>
      Meu nome é: {{ nome }}
  </h1>
</template>

<script>
export default {
  name: 'LyfeCycle',
  data(){
      return{
          nome:'Ainda não sei'
      }
  },
  created() {
      setTimeout(() =>{
          this.nome ="Pedro"
      }, 1000)
     
  },
  mounted(){
      setTimeout(() =>{
          this.nome ="Matheus"
      }, 2000)
  }
}
</script>
>>>>>>> a38ebb375cb66181eea7241899e8f73a188768c2
