<template>
<div>
  <span v-if="seen">Now you see me </span>
</div>
</template>

<script>
export default {
  name: 'conditional',
  data() {
    return {
      seen: true
    }
  }
}
</script>

<style> 

</style>