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

#app {
  background: #DCF5FF;
  margin: 0;
  height: 100vh;
  display: grid;
  justify-items: center;
  align-items: center;
  font-family: 'Nunito', 'sans-serif'
}
</style>
