<template>
  <div id="app">
  <div id="heading">
  <h1> Covid Face Mask Detection</h1>
 </div>
 <div id="description">
 The virus is spread at an alarming rate without the knowledge of the infected person. Covid-19 spreads when infected person coughs, sneezes or talks and droplets from their mouth or nose are launched into air and land in the “T Zone(Eyes, Nose, Mouth)” of people nearby. Therefore, wearing Mask is necessary step to be taken for safety of humanity as masks are the safety shield from the transfer of droplets. The usage of masks is the best and most effective method to stop the transfer of virus directly safeguarding self and others.
 </div>
 <div id="wrapper">
    <h1> Face Mask Detection</h1>
    
        <Capture/>
        
  </div>
  <div id="row1">
  <div id="surgical-card">
  <h1>Surgical mask</h1>
  <img src="./surge.jpeg" alt = "surgical mask" height="50" width="70">
  
    </div>
    <div id="InvalidMask-card">
    <h1>Invalid mask</h1>
    <img src="./invalid.jpg" alt = "invalid mask" height="50" width="70">
    </div>
    </div>
    
    <div id="row1">
  <div id="surgical-card">
  <h1>N95-mask</h1>
  <img src="n95.jpg" alt = "n95-mask" height="50" width="70">
  
    </div>
    <div id="InvalidMask-card">
    <h1>Fasion/cloth mask</h1>
    <img src="cloth.jpg" alt = "cloth-mask" height="50" width="70">
    </div>
     </div>
   <div id="statics-heading">
   Statics
   </div>
   <div>
    <ChartBar />
   </div>
    
    
  </div>
</template>

<script>

import Capture from './components/Capture.vue';
import ChartBar from './components/ChartBar.vue';


export default {
  name: 'app',
  components: {
    Capture,
    ChartBar
  }
}
</script>
<style lang="css">
</style>
<style>
@import url('https://fonts.googleapis.com/css?family=Raleway');
body, html {
  padding: 10px;
  margin: 0;
  background: linear-gradient(150deg,#281483 15%,#8f6ed5 70%,#d782d9 94%);
overflow-x:hidden;
}
h1{
text-align:center;
}
#app {
  font-family: 'Raleway';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
}
#wrapper{
margin-top:30px;
flex-direction: column;
    box-shadow: 0 8px 10px 1px rgba(0, 0, 0, .14), 0 3px 14px 2px rgba(0, 0, 0, .12), 0 5px 5px -3px rgba(0, 0, 0, .3);
    width: 95%;
    display: flex;
    padding-bottom: 30px;
 }
 #heading{
 display:flex;
 justify-content:center;
 }
 #row1{
 
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    position: relative;
 }
 #surgical-card
{ 
   width:44%;
   display: flex;
   margin-right: 20px;
    margin-top: 80px;
    align-items: center;
    flex-direction: column;
    padding: 0 30px 30px 30px;
    box-shadow: 0 0 10px #444;
}
#InvalidMask-card{
display: flex;
width:44%;
    margin-top: 80px;
    align-items: center;
    flex-direction: column;
    padding: 0 30px 30px 30px;
    box-shadow: 0 0 10px #444;

}

</style>
