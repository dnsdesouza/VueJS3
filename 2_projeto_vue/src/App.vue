<<<<<<< HEAD
<template>
    <primeiro-componente />
    <div>
        O dado de app é {{ testando }}
        <LifeCycle />
        <Pessoa />
    </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue';
import Pessoa from './components/Pessoa.vue';
import Form from './components/Form.vue'

export default {
    name: 'App',
    components: { 
        PrimeiroComponente,
        LifeCycle,
        Pessoa,
        Form
    },
    data() {
        return {
            testando: "Teste"
        }
    }
}
</script>
=======
<template>
  <div>
    <PrimeiroComponente />
    <p>O dado é: {{ testando}}</p>
    <LifeCycle />
    <Pessoa />
  </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Pessoa from './components/Pessoa.vue'

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    Pessoa
  },
  data() {
    return{
      testando: "Teste"
    }
  }
}
</script>
>>>>>>> a38ebb375cb66181eea7241899e8f73a188768c2
