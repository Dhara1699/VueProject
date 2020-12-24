<template>
  <div id="app">
    <img alt="butterfly" src="./assets/butterfly.png">
    <Home data = "My New Butterfly Page" msg="Hi, I'm Dhara"/>  
  </div>
</template>

<script>
 //import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
  //  HelloWorld,
    Home 
  }
}
</script>

<style>
#app {
  font-family: Avenir,'Times New Roman', serif, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #aeb4b9;
  margin-top: 60px;
}
</style>
