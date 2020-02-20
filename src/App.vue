<template>
  <div id="app">
    <Istagram />
  </div>
</template>

<script>
import Istagram from './components/Instagram'

export default {
  name: 'App',
  components: {
    Istagram
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
}
</style>
