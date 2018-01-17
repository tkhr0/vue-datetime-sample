<template>
  <Datetime/>
</template>

<script>
import { Datetime } from 'vue-datetime'
import 'vue-datetime/dist/vue-datetime.css'

Vue.extend({
  template: 'Datetime',
  components: {
    datetime: Datetime
  }
})

</script>

<style scoped>
</style>
