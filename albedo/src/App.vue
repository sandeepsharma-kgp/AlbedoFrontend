<template>
  <div id="app">
    <Navbar />
    <Carousel />
    <Courses />
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Carousel from './components/Carousel'
import Courses from './components/Courses'

export default {
  name: 'app',
  components: {
    Navbar,
    Carousel,
    Courses
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
