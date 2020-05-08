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
  <p>Surgical mask help to block large-particle droplets, splashes, sprays, or splatter that may contain viruses and bacteria, keeping it from reaching the wearer's mouth and nose. Surgical masks are effective barriers for retaining large droplets released from the mouth and nose by the wearer in public.  Surgical masks help reduce exposure of the wearer's saliva and respiratory. secretions to others that could otherwise travel up to 26 feet. Surgical mask also remind wearers not to touch their mouth or nose, which could otherwise transfer viruses and bacteria after having touched a contaminated surface.
    </p>
    </div>
    <div id="N95Mask-card">
    <h1>Surgical mask</h1>
    <p>N stands “Non-Oil” meaning that if no oil-based particulates are present, 95: means having a 95 percent efficiency.  N95 mask can filter 95% of particles that are 100-300 nm in size.
    </p>
    </div>
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
  margin: 0;
  background: linear-gradient(150deg,#281483 15%,#8f6ed5 70%,#d782d9 94%);
overflow-x:hidden;
}
h1{
text-align:center;
}
#app {
  font-family: 'Roboto Condensed', sans-serif;
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
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    position: relative;
 }
 #surgical-card
{
   display: flex;
    margin-top: 100px;
    align-items: center;
    flex-direction: column;
    padding: 0 30px 30px 30px;
    box-shadow: 0 0 10px #444;
}
#N95Mask-card{
display: flex;
    margin-top: 100px;
    align-items: center;
    flex-direction: column;
    padding: 0 30px 30px 30px;
    box-shadow: 0 0 10px #444;

}

</style>
