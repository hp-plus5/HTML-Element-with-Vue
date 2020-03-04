<template>
  <div id="app">
    <blink><h1>text blinks here</h1></blink>
  </div>
</template>

<script>
import Blink from './components/Blink';

export default {
  components: {
    Blink
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
