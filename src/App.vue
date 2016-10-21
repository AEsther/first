<template>
  <div id="app">
      <header1></header1>
      <navbar></navbar>
      <rightbar></rightbar>
  </div>
</template>

<script>
import header1 from './components/top'
import navbar from './components/left'
import rightbar from './components/right'

export default {
  name: 'app',
  components: {
    header1,navbar,rightbar
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
