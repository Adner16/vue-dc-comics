<template>
    <div class="background">
        <div class="container">
            <ul v-for="card in cards" :key="card.text" class="card-img">
                <li>
                    <figure>
                        <img 
                            :src="require(`../assets/img/${card.url}`)" 
                            :alt="card.description"
                        />
                    </figure>
                    <span class="text">{{ card.text }}</span>
                </li>
                <!-- <li> -->
                    <!-- <figure>
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
                </li> -->
            </ul>
        </div>
    </div>  
</template>

<script>
export default {
    name: 'Nav',
    data() {
        return {
            cards:[
                {
                    text: 'DIGITAL COMICS',
                    url: 'buy-comics-digital-comics.png',
                    description: 'logo dc',
                },
                {
                    text: 'DC MERCHANDISE',
                    url: 'buy-comics-merchandise.png,',
                    description: 'logo merchandise',
                },
                {
                    text: 'SUBSCRIPTION',
                    url: 'buy-comics-subscription.png',
                    description: 'logo subscription',
                },
                {
                    text: 'COMIC SHOP LOCATOR',
                    url: 'buy-comics-shop-locator.png',
                    description: 'logo shop',
                },
                {
                    text: 'DC POWER VISA',
                    url: 'buy-dc-power-visa',
                    description: 'logo visa',
                },
            ],
        };
    },
};
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