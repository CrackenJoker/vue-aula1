<template>
        <div>
            <h1>Ola meu nome é {{ nome }} <LifeCycle/> </h1><br>
            <h3>Trabalho como {{ profissao }}</h3>
        </div>
</template>
<script>
import LifeCycle from './LifeCycle.vue';
export default{
    name:'PrimeiroComponente',
    components:{
        LifeCycle
    },
    data() {
        return {
            nome:'Joelson',
            profissao:'TI'
        }
    },
}
</script>