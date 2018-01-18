<template>
  <div>
    <ol>
      <li v-for="todo in todos"
        :key="todo.id">
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
          { id: 0, text: 'thing 1'},
          { id: 1, text: 'thing 2'},
          { id: 2, text: 'thing 3'}
        ]
      }
    }
  }
</script>

<style> 

</style>