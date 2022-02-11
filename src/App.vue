<template>
  <div id="app">
   <Header />
   <Jumbo />
   <Main />
   <Nav />
   <Footer />
   <Social />
  </div>
</template>

<script>
import Header from  './components/Header'
import Main from './components/Main'
import Nav from './components/Nav'
import Footer from './components/Footer'
import Social from './components/Social'
import Jumbo from './components/Jumbo'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Nav,
    Footer,
    Social,
    Jumbo,
  }
}
</script>

<style lang="scss">
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  img{
    width: 100%;
    height: auto;
  }
</style>
