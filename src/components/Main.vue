<template>
  <div class="background">
      <div class="container">
          <p>content goes here</p>
      </div>
      
  </div>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<style scoped lang='scss'>

    .background {
                background-color: #1c1c1c;
                height: 100px;
                display: flex;
                align-items: center;
        .container{
            width: 1200px;
            margin: auto;
            color: white;
            
            p {
                font-weight: 600;
                font-size: 20px;
            }
        }
    }
</style>