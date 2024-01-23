<template>
  <navbar />
  <br> <br> <br>
  <div>
    <eventsButton />
    <div class="events">
      <BoxCard1 /> <BoxCard2 /> <BoxCard3 /> 
    </div>
  </div>
  <div>
    <sponsorsButton />
    <div class="events">
      <BoxCard4 /> <BoxCard5 />  elle evede
    </div>
  </div>
  
  <fooTer />
</template>

<script setup>
  import BoxCard1 from './components/BoxCard1.vue'
  import BoxCard2 from './components/BoxCard2.vue'
  import BoxCard3 from './components/BoxCard3.vue'
  import BoxCard4 from './components/BoxCard4.vue'
  import BoxCard5 from './components/BoxCard5.vue'
  import navbar from './components/navbar.vue'
  import eventsButton from './components/eventsButton.vue'
  import sponsorsButton from './components/sponsorsButton.vue'
  import fooTer from './components/fooTer.vue'
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  justify-content: center;
  align-items: center;
  text-align: center;
  /* background-color: #F1CCD7; */
  background-image: url(./components/assets/5.jpg);
  
  background-size:cover;
  color: #2c3e50;
}
.events{
  display: flex;
  justify-content: space-evenly;
  justify-items: center;
  margin: 20px;
}
</style>
