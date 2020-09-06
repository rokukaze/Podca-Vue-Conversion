<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <PodcaFooter/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PodcaFooter from './components/PodcaFooter.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, PodcaFooter
  }
}
</script>

<style>
/* Removed for proper podca formatting */
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
