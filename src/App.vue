<template>
  <div>
    <PrimeiroComponente/>
    <Idade/>
  </div>
</template>
<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import Idade from './components/Idade.vue'
export default {
  name:'App',
  components:{
    PrimeiroComponente,
    Idade
  }
}
</script>