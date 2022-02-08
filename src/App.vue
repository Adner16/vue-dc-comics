<template>
  <div id="app">
   <Header />
  </div>
</template>

<script>
import Header from  './components/Header'

export default {
  name: 'App',
  components: {
    Header
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
