<template>
  <div id="app">
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from './HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Nunito&display=swap');
body{
  margin: 0!important;
}
#app {
  background: #DCF5FF;
  margin: 0;
  height: 100vh;
  width: 100vw;
  display: flex;
  font-family: 'Nunito', 'sans-serif'
}
</style>
