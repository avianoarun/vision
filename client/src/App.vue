<template>
  <div id="app">
    <h1> Covid Face Mask Detection</h1>
        <Capture/>
  </div>
</template>

<script>

import Capture from './components/Capture.vue';


export default {
  name: 'app',
  components: {
    Capture
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');
body, html {
  padding: 10px;
  height:100vh;
  width:100vw;
  margin: 0;
  background: linear-gradient(150deg,#281483 15%,#8f6ed5 70%,#d782d9 94%);
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
