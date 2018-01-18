<template>
  <li>{{ list.text }}</li>
</template>

<script>
export default {
  name: 'prop',
  props: {
    list: {
      type: Object
    }
  }
}
</script>

<style> 
</style>