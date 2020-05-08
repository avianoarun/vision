<template>
  <div id="app">
  <div id="heading">
  <img v-bind:src="'https://spaceplace.nasa.gov/templates/featured/sun/' + hello" width="200"/>
  <h1> Covid Face Mask Detection</h1>
  </div>
  <div id="wrapper">
    <h1> Face Mask Detection</h1>
        <Capture/>
  </div>
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
  overflow-x:hidden;
}
#app {
  font-family: 'Roboto Condensed', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 50px;
}
#wrapper{
flex-direction: column;
    box-shadow: 0 8px 10px 1px rgba(0, 0, 0, .14), 0 3px 14px 2px rgba(0, 0, 0, .12), 0 5px 5px -3px rgba(0, 0, 0, .3);
    width: 95%;
    display: flex;
    padding bottom:30px;
    }
 #heading{
 display:flex;
 }
</style>
