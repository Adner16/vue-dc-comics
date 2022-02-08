<template>
  <div id="app">
   <Header />
   <Main />
  </div>
</template>

<script>
import Header from  './components/Header'
import Main from './components/Main'

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style lang="scss">
  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

</style>
