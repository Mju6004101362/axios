<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo1.png">
   <!-- <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <music/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import music from './components/music'
export default {
  name: 'App',
  components: {
    //HelloWorld,
    music

}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
