<template>
  <div id="app">
    <MainApp/>
  </div>
</template>

<script>
import MainApp from './main/MainApp.vue'
export default {
  name: 'App',
  components: {
    MainApp
  }
}
</script>

<style>
  @import './assets/css/style.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
