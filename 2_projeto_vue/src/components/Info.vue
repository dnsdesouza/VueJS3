<<<<<<< HEAD
<template>
<div>
    <p v-if="esta_trabalhando">Estou trabalhando </p>
    <p v-else>Estou em busca de novas oportunidades!</p>
    <p>Utilizo as seguintes tecnologias</p>
        <ul>
            <li>JavaScript</li>
            <li>PHP</li>
            <li>Pyton</li>
        </ul>
        <p v-show="mostrar_email" >Mande uma mensagem para: {{ email }}</p>
        <p>Para acessar meu portifólio <a :href="meu_link" target="_blank">cilique aqui</a></p>
        <Picture />
</div>
</template>
<script >
import Picture from './Picture.vue'

export default {
    name:'Info',
    components:{
        Picture
    },
    data(){
        return{
            esta_trabalhando:false,
            mostrar_email: true,
            email:'matheus@gmail.com',
            mostrar_email:true,
            meu_link: 'http://google.com'
        }
    }
}
=======
<template>
    <div>
        <p>Estou trabalhando no momento.</p>
        <p>Utilizo as seguintes tecnologias:</p>
        <ul>
            <li>JavaScript</li>
            <li>PHP</li>
            <li>PYTON</li>
        </ul>
    </div>
</template>
<script >
    export default{
        name: 'Info'
    }
>>>>>>> a38ebb375cb66181eea7241899e8f73a188768c2
</script>