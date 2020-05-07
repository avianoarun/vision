<template>
  <div id="app">
    <h1> Covid Face Mask Detection</h1>
    <Capture/>
  </div>
</template>

<script>
import Capture from './components/Capture.vue'

export default {
  name: 'app',
  components: {
    Capture
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
}
</style>
