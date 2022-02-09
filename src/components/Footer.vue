<template>
    <div class="background">
        <div class="container">
            <div class="col-50-left">
                <ul>
                    <li>
                        <h3>DC COMICS</h3>
                    </li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <li>
                        <h3>SHOP</h3>
                    </li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
                <ul>
                    <li>
                        <h3>DC</h3>
                    </li>
                    <li>Terms of use</li>
                    <li>Privacy Policy (new)</li>
                    <li>Ad choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact us</li>
                </ul>
                <ul>
                    <li>
                        <h3>SITES</h3>
                    </li>
                    <li>DC</li>
                    <li>MAD Megazine</li>
                    <li>DC kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
            <div class="col-50-right">

            </div>
           
        </div>
    </div>
    
    
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style scoped lang='scss'>

    .background{
        background-image: url("../assets/img/footer-bg.jpg");
        background-size: cover;
        background-position: center;
    };
    .container{
        height: 400px;
        width: 1200px;
        margin: auto;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        .col-50-left{
        width: 50%;
        padding: 30px 0;
            ul {
            list-style-type: none;
                li{
                    color: grey;
                    font-size: 15px;
                    h3{
                        margin: 15px 0;
                        color: white;
                    }
                }
            }
        }
        .col-50-right{
            width: 100%;
            height: 100%;
            background-image: url('../assets/img/dc-logo-bg.png');
            background-position: center;
            background-size: 600px;
            background-repeat: no-repeat;
        }   
    }
</style>