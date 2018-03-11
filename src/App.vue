<template>
  <div id="app">
    <m-header></m-header>
  </div>
</template>

<script>
import mHeader from './components/header/m-header'
  export default {
    components: {
      mHeader
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
