<template>
  <div id="app">
    <introduction/>
    <binding/>
  </div>
</template>

<script>
import introduction from './components/introduction'
import binding from './components/binding'

export default {
  name: 'App',
  components: {
    introduction,
    binding
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
