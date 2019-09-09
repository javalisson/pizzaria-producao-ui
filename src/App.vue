<template>
  <div id="app">
    <Navegacao />
    <router-view/>
  </div>
</template>

<script>
import Navegacao from '@/components/Navegacao'

export default {
  name: 'app',
  components: {
    Navegacao
  }
}
</script>

<style lang="scss">
@import "./assets/styles/custom";
@import "../node_modules/bootstrap/scss/bootstrap";

</style>
