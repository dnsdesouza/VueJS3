<template>
<div>
    <h2>Esta é a descricção da pessoa:{{ nome }} </h2>
    <p>Estou trabalhando </p>
    <p>Utilizo as seguintes tecnologias</p>
        <ul>
            <li>JavaScript</li>
            <li>PHP</li>
            <li>Pyton</li>
        </ul>
</div>
</template>

<script>
export default {
    name: 'PessoaQualquer',
    data() {
        return {
            nome: "MatheusQualquer"
        }
    }
}


</script>
