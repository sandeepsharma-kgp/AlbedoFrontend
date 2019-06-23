<template>
  <div id="app">
    <LandingPage />
    <Advertisements />
  </div>
</template>

<script>
import LandingPage from './components/LandingPage'
import Advertisements from './components/Advertisements'

export default {
  name: 'app',
  components: {
    LandingPage,
    Advertisements
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