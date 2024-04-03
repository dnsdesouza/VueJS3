<template>
<<<<<<< HEAD
  <div>
    <PrimeiroComponente/>
    <p>O dado de app é: {{testando}}</p>
    <LifeCycle />
    <Pessoa />
  </div>
</template>

<script>

import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Pessoa from './components/Pessoa.vue'
  
  export default{
    name:'App',
    components:{
      PrimeiroComponente,
      LifeCycle,
      Pessoa
    },
    data(){
      return{
        testando:"Teste de dentro do App.vue"
      }
    }
  }
</script>
=======
  <TheHeader  v-if="showHeader" />

  <div v-show="showName">
    Nome: {{firstname}}  <br>
    Sobrenome:{{ lastName}}
  </div>
  <div v-if="accessLevel === 'admin'">Admin</div>
  <div v-else-if="accessLevel === 'marketing'">Marketing</div>
  <div v-else>User</div>

  <img 
    alt="Vue logo" 
    src="./assets/logo.png"
  >
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TheHeader from './components/TheHeader';

export default {
  name: 'App',
  components: {
    HelloWorld,
    TheHeader
  },
  data(){
    return{
      showHeader: true,
      firstname:'Jhon' ,
      lastName: 'Snow',
      showName:true,
      accessLevel: 'marketing'
    }
  }


}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
>>>>>>> af4d9caacb7deb41d728e96785535b90d1feb687
