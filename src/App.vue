<template>
  <mi-componente-1></mi-componente-1>
  <miComponente2></miComponente2>
  <mi-componente-3></mi-componente-3>
</template>

<script>
import miComponente1 from './components/background.vue'
import miComponente2 from './components/login.vue'
import miComponente3 from './components/opciones.vue'

export default {
  name: 'App',
  components: {
    miComponente1,
    miComponente2,
    miComponente3
  }
}

</script>

<style lang='scss'>

</style>
