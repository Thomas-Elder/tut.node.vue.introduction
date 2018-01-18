<template>
  <div>
    <p>{{ message }}</p>
    <button v-on:click="reverseMessage">Reverse Message </button>

    <p>{{ differentMessage }}</p>
    <input v-model="differentMessage">
  </div>
</template>

<script>
  export default {
    name: 'userInput',
    data() {
      return {
        message: 'Hello everybody',
        differentMessage: 'This is a different message'
      }
    },
    methods: {
      reverseMessage() {
        this.message = this.message.split(' ').reverse().join(' ')
      }
    }
  }
</script>

<style> 

</style>