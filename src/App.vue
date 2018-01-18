<template>
  <div id="app">
    <introduction/>
    <binding/>
    <conditional/>
    <loop/>
    <userInput/>
    <ol>
      <prop
        v-for="item in list"
        v-bind:prop="item"
        v-bind:key="item.id">
      </prop>
    </ol>
  </div>
</template>

<script>
import introduction from './components/introduction'
import binding from './components/binding'
import conditional from './components/conditional'
import loop from './components/loop'
import userInput from './components/userInput'
import prop from './components/prop'

export default {
  name: 'App',
  components: {
    introduction,
    binding,
    conditional,
    loop,
    userInput,
    prop
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
