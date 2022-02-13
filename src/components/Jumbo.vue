<template>
  <div class="background">
    <div class="container">
            <button class="btn">CURRENT SERIES</button>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Jumbo',
}
</script>

<style scoped lang='scss'>
  .background {
    background-image: url('../assets/img/jumbotron.jpg');
    background-position: center;
    background-position: top ;
    height: 320px;
    .container {
      width: 1200px;
      height: 100%;
      margin: auto;
      position: relative;

      .btn{
      background-color: dodgerblue;
      color: white;
      padding: 10px;
      position: absolute;
      bottom: -20px;

    }
  }
    
  }
</style>