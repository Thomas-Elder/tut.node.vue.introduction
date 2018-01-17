<template>
<div>
  <p>{{ message }}</p>
  <button v-on:click="reverseMessage">Reverse Message </button>
</div>
</template>

<script>
  export default {
    name: 'userInput',
    data() {
      return {
        message: 'Hello everybody'
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