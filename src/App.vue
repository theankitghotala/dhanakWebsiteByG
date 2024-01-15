<template>
  <navbar />
  <br> <br> <br>
  <div>
    <eventsButton />
    <div class="events">
      <BoxCard /> <BoxCard /> <BoxCard /> 
    </div>
  </div>
  <div>
    <sponsorsButton />
    <div class="events">
      <BoxCard /> <BoxCard /> <BoxCard /> 
    </div>
  </div>
  
  <fooTer />
</template>

<script setup>
  import BoxCard from './components/BoxCard.vue'
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
  /* background-color: rgb(0, 119, 179); */
  background-image: url(./components/assets/5.jpg);
  background-size: cover;
  color: #2c3e50;
}
.events{
  display: flex;
  justify-content: space-evenly;
  justify-items: center;
  margin: 20px;
}
</style>
