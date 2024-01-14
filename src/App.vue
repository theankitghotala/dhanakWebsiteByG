<template>
  <navbar />
  <div>
    <clickableButton />
  <div class="events">
    <BoxCard /> <BoxCard /> <BoxCard /> 
  </div>
  </div>
  
  
</template>

<script setup>
  import BoxCard from './components/BoxCard.vue'
  import navbar from './components/navbar.vue'
  import clickableButton from './components/clickableButton.vue'

</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: rgb(234, 109, 20);
  color: #2c3e50;
}
.events{
  display: flex;
  justify-content: space-evenly;
  justify-items: center;
  margin: 20px;
}
</style>
