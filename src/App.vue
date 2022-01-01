<template>
  <div id="app">
      <header_desk/>
    <footer_desk/>
  </div>
</template>

<script>
import header_desk from './components/header_desk.vue'
import Footer_desk from "./components/footer_desk";

export default {
  name: 'App',
  components: {
    Footer_desk,
    header_desk
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
