<template>
  <li>{{ item.text }}</li>
</template>

<script>
export default {
  name: 'prop',
  props: {
    item: {
      type: Object
    }
  }
}
</script>

<style> 
</style>