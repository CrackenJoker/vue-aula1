<template>
    <div>
        <p>Sou programador Profissional há {{ idade }}</p>
        <p v-if="idade>6">Sou truta na materia</p>
    </div>
</template>
<script>
export default{
    name:'Idade',
    data(){
        return{
            idade:6
        }
    }
}
</script>