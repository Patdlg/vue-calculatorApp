<template>
  <div id="app">
  <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'
export default {
  name: 'App',
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
  color: #2c3e50;
  margin-top: 60px;
}

body {
  background: url(https://us.123rf.com/450wm/belchonoksun/belchonoksun1603/belchonoksun160300011/53036605-stock-vector-multicolored-mathematical-vector-seamless-pattern-with-geometrical-plots-formulas-and-calculations-m.jpg?ver=6);

}
</style>
