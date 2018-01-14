<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
require('material-design-lite')
export default {
  name: 'app'
}
</script>

<style>

body {
  background-color: #0097A7;
  font-family: 'Nunito', sans-serif;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

ul {
  display: block;
  width: 100%;
}

li {
  display: inline-block;
  width: 33%;
}
</style>
