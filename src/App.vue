<template>
  <div id="app">
    <intro></intro>
    <capture></capture>
    <article></article>
  </div>
</template>

<script>
import Intro from './components/Intro'
import Capture from './components/Capture'

export default {
  name: 'app',
  components: {
    Intro,
    Capture
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 60px;
}
</style>
