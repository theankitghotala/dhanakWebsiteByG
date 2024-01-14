<template>
  <navbar />
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js Application"/>
  <BoxCard />
</template>

<script setup>
  import BoxCard from './components/BoxCard.vue'
  import navbar from './components/navbar.vue'
</script>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
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
</style>
