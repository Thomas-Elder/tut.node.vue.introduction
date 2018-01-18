<template>
  <li>{{ list.text }}</li>
</template>

<script>
export default {
  name: 'prop',
  data() {
    return {
      list:[
        { id: 0, text: 'Apple' },
        { id: 1, text: 'Banana' },
        { id: 2, text: 'Pear' }
      ]
    }
  },
  props: ['list']
}
</script>

<style> 

</style>