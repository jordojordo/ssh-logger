<template>
  <div id="app">
    <sshReader />
  </div>
</template>

<script>
import sshReader from './components/sshReader'

export default {
  name: 'App',
  components: {
    sshReader
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
