<template>
  <div id="app">
    <Navbar />
    <Advertisements />
    <Blogs />
    <Footer />
    <ContactUs />
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Advertisements from './components/Advertisements'
import Blogs from './components/Blogs'
import Footer from './components/Footer'
import ContactUs from './components/ContactUs'


export default {
  name: 'app',
  components: {
    Navbar,
    Advertisements,
    Blogs,
    Footer,
    ContactUs
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