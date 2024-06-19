<template>
    <div>
        <p>Meu outro Nome é {{ nome }}</p>
    </div>
</template>
<script>
export default{
    name:'LifeCycle',
    data(){
        return{
            nome:'Não sei ainda'
        }
    },
    created(){
        setTimeout(()=>{
            this.nome = 'Carvalho'
        },1000)
    },
    mounted(){
        setTimeout(()=>{
            this.nome = 'Candomba'
        },2000)
    }
}
</script>