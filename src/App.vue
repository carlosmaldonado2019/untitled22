<template>
  <div id="app" class="container">

    <Cabecera></Cabecera>
    <Lista></Lista>
  </div>
</template>

<script>

import Cabecera from "./components/Cabecera.vue";
import Lista from "./components/Lista";

export default {
  name: 'app',
  components: {
    Cabecera,
    Lista
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
