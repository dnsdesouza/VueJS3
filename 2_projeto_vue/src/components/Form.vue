<<<<<<< HEAD
<template>
    <div>
    <h2>Meu formulário: #08</h2>
    <form action="">
       <div>
        <InputText/>
       </div> 
       <div>
        <InputText/> 
       </div>
       <div>
        <Submit/>
       </div>         
    </form>
    </div>
</template> 

  
<script>
import InputText from './form/InputText.vue'
import Submit from './form/Submit.vue'       
    
    export default{
        name: 'Form',
        components:{
            InputText,
            Submit
        }

    }

=======
<template>
    <form action="">
        <div><InputText /></div> 
        <div><InputText /></div> 
        <div><Submit /></div>  

    </form>
  
  
</template> 

<script>
import InputText from './form/InputText.vue'
import Submit from './form/Submit.vue'

    export default{
        name: 'Form',
        components:{
            InputText,
            Submit
        }
    }
>>>>>>> a38ebb375cb66181eea7241899e8f73a188768c2
</script>