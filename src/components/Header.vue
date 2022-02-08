<template>
  <header>
      <div class="container">
           <figure>
          <img src="../assets/img/dc-logo.png" alt="">
      </figure>
      <ul>
          <li>
              <a href="#">CHARACTERS</a>
          </li>
          <li class="active">
              <a href="#">COMICS</a>
          </li><li>
              <a href="#">MOVIES</a>
          </li><li>
              <a href="#">TV</a>
          </li><li>
              <a href="#">GAMES</a>
          </li><li>
              <a href="#">COLLECTIBLES</a>
          </li><li>
              <a href="#">VIDEO</a>
          </li><li>
              <a href="#">FANS</a>
          </li><li>
              <a href="#">NEWS</a>
          </li><li>
              <a href="#">SHOP</a>
          </li>

      </ul>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style lang='scss'>
    header .container{
        width: 1200px;
        margin: auto;
        display: flex;
        justify-content: space-between;
        padding: 10px;

        ul{
            display: flex;
            align-items: center;

            li{
                margin: 5px;
                list-style-type: none;
                a{
                    color: black;
                    text-decoration: none;
                }
            }
        }
    }
</style>