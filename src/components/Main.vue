<template>
<div class="app">
    <div class="container">
        <h1>Content goes here</h1>
    </div>
    <div class="directions">
        <div class="img">
            <img src="@/assets/buy-comics-digital-comics.png" alt="">
            <div class="testo">DIGITAL COMICS</div>
        </div>
        <div class="img">
            <img src="@/assets/buy-comics-merchandise.png" alt="">
            <div class="testo">DC MERCANDISE</div>
        </div>
        <div class="img">
            <img src="@/assets/buy-comics-subscriptions.png" alt="">
            <div class="testo">SUBSCRIPTION</div>
        </div>
        <div class="img">
            <img src="@/assets/buy-comics-shop-locator.png" alt="">
            <div class="testo">COMIC SHOP LOCATOR</div>
        </div>
        <div class="img">
            <img src="@/assets/buy-dc-power-visa.svg" alt="">
            <div class="testo">DC POWER VISA</div>
        </div>
    </div>
    <div class="menu">
        <div class="container">
            <div class="left">
                <div class="column">
                    <h3>DC COMICS</h3>
                    <p>Characters</p>
                    <p>Comocs</p>
                    <p>Movies</p>
                    <p>TV</p>
                    <p>Games</p>
                    <p>Videos</p>
                    <p>News</p>
                    <h3>SHOP</h3>
                    <p>Shop DC</p>
                    <p>Shop DC Collectibles</p>
                
                </div>
                <div class="column">
                    <h3>DC COMICS</h3>
                    <p>Characters</p>
                    <p>Comocs</p>
                    <p>Movies</p>
                    <p>TV</p>
                    <p>Games</p>
                    <p>Videos</p>
                    <p>News</p>
                </div>
                <div class="column">
                    <h3>DC COMICS</h3>
                    <p>Characters</p>
                    <p>Comocs</p>
                    <p>Movies</p>
                    <p>TV</p>
                    <p>Games</p>
                    <p>Videos</p>
                    <p>News</p>
                </div>

            </div>
            <div class="right">
                <img src="@/assets/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>

</div>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<style scoped lang="scss">
@import '@/styles/utilities';
@import '@/styles/vars';

.app{
    background: $colorGrey;
    .directions{
    display: flex;
    align-items: center;
    justify-content: center;
    padding:30px 0;
    background: $colorBlue;
        .img{
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 0 14px;
            img{
                width: 40px;
                cursor: pointer;
            }
            .testo{
                color:white;
                font-size: 18px;
                margin-left:10px;
            }
        }

    }
    .menu{
        background-image:url(../assets/footer-bg.jpg);
        background-position: center;
        background-size:cover;
        height: 400px;
        .container{
            display: flex;
            justify-content: space-between;
            .left{
                display: flex;

                .column{
                    width:calc(100%/3);
                    height: 3px;
                    padding: 25px 10px;
                    h3{
                        color: white;
                        margin: 10px 0;
                    }
                    p{
                        color:gray;
                        font-size: 14px;
                        padding:3px 0;
                    }
                }
            }
            .right{
                img{
                    width: 500px;
                    position: relative;
                    top:-50px;
                }
            }
        }
    }
}

</style>