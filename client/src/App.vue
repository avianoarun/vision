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
body, html {
  padding: 0;
  margin: 0;
  width: 100%;
  background: linear-gradient(150deg,#281483 15%,#8f6ed5 70%,#d782d9 94%);
  min-height: 100%; // add this rule
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
}
</style>
