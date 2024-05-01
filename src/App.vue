<template>
  <Navbar/>
  <Header/>
  <Main/>
  <Footer/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
   Navbar,
   Header,
   Main,
   Footer
  }
}
</script>

<style>


* {
    margin: 0;
    padding: 0;
    text-decoration: none;
    list-style: none;
    box-sizing: border-box;
    font-family: 'Roboto-Regular';
}

body {
    background: #040D1F;

}
</style>
