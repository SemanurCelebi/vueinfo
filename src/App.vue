<template>
  <div id="app">
<!--    <img alt="Vue logo" src="./assets/logo.png">-->
    <TheHeader />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TheHeader from './components/TheHeader'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TheHeader
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
}
</style>
