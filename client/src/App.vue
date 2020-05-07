<template>
  <div id="app">
    <h1> Covid Face Mask Detection</h1>
    <Capture/>
  </div>
</template>

<script>
import Capture from './components/Capture.vue'
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');

export default {
  name: 'app',
  components: {
    Capture
  }
}
</script>

<style>
body, html {
  padding: 10px;
  height: 100%;
  margin: 0;
  width: 100%;
  background: linear-gradient(150deg,#281483 15%,#8f6ed5 70%,#d782d9 94%);
  overflow: hidden;
}
#app {
  font-family: 'Roboto Condensed', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
}
</style>
