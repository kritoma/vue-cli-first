<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <baseTitle/>
  </div>
</template>

<script>
import baseTitle from './components/baseTitle.vue' 

export default {
  name: 'App',
  components: {
    baseTitle
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
