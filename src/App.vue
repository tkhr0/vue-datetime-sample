<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <Datetime v-model="datetime" type="datetime" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import 'vue-datetime/dist/vue-datetime.css'

export default {
  name: 'App',
  components: {
    HelloWorld
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
