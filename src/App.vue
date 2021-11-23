<template>
  <div id="app">
    <testTitle/>
    <testImage/>
  </div>
</template>

<script>
import testTitle from './components/testTitle.vue';
import testImage from './components/testImage.vue';

export default {
  name: 'App',
  components: {
    testTitle,
    testImage
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
