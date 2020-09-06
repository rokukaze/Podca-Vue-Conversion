<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <FeaturedGuests/>
    <SubscribeBanner/>
    <PodcaFooter/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PodcaFooter from './components/PodcaFooter.vue'
import SubscribeBanner from './components/SubscribeBanner.vue'
import FeaturedGuests from './components/FeaturedGuests.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, PodcaFooter, SubscribeBanner, FeaturedGuests
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
