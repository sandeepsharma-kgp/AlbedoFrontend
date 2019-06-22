<template>
  <div id="app">
    <LandingPage />
    <Carousel />
  </div>
</template>

<script>
import LandingPage from './components/LandingPage'
import Carousel from './components/Carousel'

export default {
  name: 'app',
  components: {
    LandingPage,
    Carousel
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
  margin: 0px;
  padding : 0px;
}
</style>
