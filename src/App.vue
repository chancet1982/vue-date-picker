<template>
  <div id="app">
    <date-picker ></date-picker >
  </div>
</template>

<script>
import DatePicker from './components/DatePicker/DatePicker'

export default {
  name: 'app',
  components: {
    DatePicker
  }
}
</script>

<style>
html,
body {
	height: 100%;
	overflow: auto;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
