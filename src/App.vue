<template>
  <div id="app">
    <introduction/>
  </div>
</template>

<script>
import introduction from './components/introduction'

export default {
  name: 'App',
  components: {
    introduction
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
