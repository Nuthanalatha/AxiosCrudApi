<template>
  <div id="app">
  <products-main />
  </div>
</template>

<script>
import ProductsMain from './components/Products-main.vue'

export default {
  name: 'App',
  components: {
   ProductsMain
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
