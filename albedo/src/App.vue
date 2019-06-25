<template>
  <div id="app">
    <Navbar />
    <HelloWord/>
    <Cards />
    <Centers/>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import HelloWord from './components/HelloWorld'
import Cards from './components/Cards'
import Centers from './components/Centers.vue'

export default {
  name: 'app',
  components: {
    Navbar,
    HelloWord,
    Cards,
    Centers
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