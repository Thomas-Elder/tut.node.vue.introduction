<template>
  <div>
    <ol>
      <li v-for="todo in todos">
        {{ todo.text }}
      </li>
    </ol>
  </div>
</template>

<script>
  export default {
    name: 'loop',
    data() {
      return {
        todos: [
          { text: 'thing 1'},
          { text: 'thing 2'},
          { text: 'thing 3'}
        ]
      }
    }
  }
</script>

<style> 

</style>