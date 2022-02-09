<template>
    <div class="background">
        <div class="container">
            <div class="link">
                <a href="">SIGN UP NOW!</a>
            </div>
            <div class="icons">
                <span>FOllOW US</span>
                <figure class="icon">
                    <img src="../assets/img/footer-facebook.png" alt="icon">
                </figure>
                <figure class="icon">
                    <img src="../assets/img/footer-twitter.png" alt="icon">
                </figure>
                <figure class="icon">
                    <img src="../assets/img/footer-youtube.png" alt="icon">
                </figure>
                <figure class="icon">
                    <img src="../assets/img/footer-pinterest.png" alt="icon">
                </figure>
                <figure class="icon">
                    <img src="../assets/img/footer-periscope.png" alt="icon">
                </figure>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Social',
}
</script>

<style scoped lang='scss'>
    .background{
        background-color: #303030;
        height: 100px;
        display: flex;
        align-items: center;
        .container{
            width: 1200px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            .link{
                border: 2px solid dodgerblue;
                background-color: #303030;
                padding: 7px;
                a{
                    color: white;
                    text-decoration: none;
                    font-size: 13px;
                }
            }
            .icons{
                display: flex;
                align-items: center;
                span{
                    color: dodgerblue;
                    margin-right: 10px;
                }
                .icon{
                    margin-left: 10px;
                    width: 30px;
                }
            }
        }
        
    }
</style>