<template>
  <v-main id="app">
    <NavBar/>
    <HelloWorld msg="Bienvenidos a mi Portfolio"/>
    <HelloWorld msg="Martin Joel Garcia"/>
  </v-main>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar/NavBar.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavBar
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
