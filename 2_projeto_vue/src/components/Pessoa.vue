<<<<<<< HEAD
<template>
<div>
    <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
    <Info />
    <Form />
</div>
</template>

<script>
    import Info from './Info'
    import Form from './Form'
 
export default {
    name: 'Pesssoa',
    components: {
        Info,
        Form
    },
    name: 'PessoaQualquer',
    data() {
        return {
            nome: "MatheusQualquer"
        }
    }
}


</script>
=======
<template>
    <div>
        <h2>Esta é a descrição da pessoa:{{ nome }} </h2>
       <Info />
       <Form />
    </div>
</template>

<script>
import Info from './Info';
import Form from './Form';

export default {
    name: 'Pessoa',
    components:{
        Info,
        Form
    },
        data(){
            return {
            nome:'Matheus'  
        }
    }   
}
   
</script>
>>>>>>> a38ebb375cb66181eea7241899e8f73a188768c2
