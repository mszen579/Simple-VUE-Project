<template>
  <div id="app">
    <img src="./assets/MSZ.png" width="100px">
    <HelloWorld msg="Hello World... Welcome to VUE"/>
    <h1>Hi, My name is Mohammad, and this is my first VUE app</h1>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
