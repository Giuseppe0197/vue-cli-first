<template>
  <div id="app">
    <testTitle/>
  </div>
</template>

<script>
import testTitle  from './components/testTitle .vue';

export default {
  name: 'App',
  components: {
    testTitle 
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
