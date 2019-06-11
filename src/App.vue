<template>
  <div id="app">
    <swipeable-cards />
  </div>
</template>

<script>
import SwipeableCards from './components/SwipeableCards.vue'

export default {
  name: 'app',
  components: { SwipeableCards }
}
</script>

<style>
body {
  margin: 0;
  z-index: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
