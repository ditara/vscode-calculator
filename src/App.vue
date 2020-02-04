<template>
  <div id="app">
    <h1 style="color: #f1e867; font-size: 50px">Calculator</h1>
    <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'app',
  components: {
    Calculator
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #4d4b3c;
  margin-top: 60px;
}
</style>
