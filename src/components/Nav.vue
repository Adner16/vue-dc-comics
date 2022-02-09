<template>
    <div class="background">
        <div class="container">
            <ul>
                <li>
                    <figure>
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="icon">
                    </figure>
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <figure>
                        <img src="../assets/img/buy-comics-merchandise.png" alt="icon">
                    </figure>
                    <span>DC MERCHANDISE</span></li>
                <li>
                    <figure>
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="logo">
                    </figure>
                    <span>SUBSCRIPTION</span></li>
                <li>
                    <figure id="locator">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="logo">
                    </figure>
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <figure>
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="logo">
                    </figure>
                    <span>DC POWER VISA</span>
                </li>
            </ul>
  </div>
    </div>
  
</template>

<script>
export default {
    name: 'Nav',
}
</script>

<style scoped lang='scss'>
    .background{
        background-color: #1e82f6;
        height: 130px;
        display: flex;
        align-items: center;
        .container{
            width: 1200px;
            margin: auto;
            display: flex;
            justify-content: center;
            ul{
                display: flex;
                align-items: center;
                flex-wrap: wrap;
                li{
                    display: flex;
                    align-items: center;
                    list-style-type: none;
                    color: white;
                    font-size: 15px;

                    #locator{
                        width: 30px;
                    }

                    figure{
                        width: 40px;
                        margin: 0 20px;
                    }
                }
            }
        }
    }
</style>