<template>
<div class="app">
    <div class="jumbotron">
    </div>
    <div class="container">
        <Card v-for="(serie, index) in series" :key=index :details="serie" />
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
                    <h3>DC </h3>
                    <p>Terms Of Use</p>
                    <p>Privacy Policy</p>
                    <p>Ad Choices</p>
                    <p>Advertising</p>
                    <p>Jobs</p>
                    <p>Subscriptions</p>
                    <p>Talent Workshops</p>
                    <p>CPSC certificates</p>
                    <p>Ratings</p>
                    <p>Shop Help</p>
                    <p>Contact Us</p>
                </div>
                <div class="column">
                    <h3>Sites</h3>
                    <p>DC</p>
                    <p>Mad Magazine</p>
                    <p>DC Kids</p>
                    <p>DC Universe</p>
                    <p>DC Power Visa</p>
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
import Card from '@/components/Card.vue';
export default {
    name: 'Main',
    components:{
        Card
    },
    data(){
        return{
            series:[
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX',
                    price: '$19.99',
                    series: 'Action Comics',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01',
                    price: '$3.99',
                    series: 'American Vampire 1976',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb',
                    price: '$16.99',
                    series: 'Aquaman',
                    type: 'graphic novel',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76',
                    price: '$2.99',
                    series: 'Batgirl',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
                    price: '$3.99',
                    series: 'Batman',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
                    price: '$2.99',
                    series: 'Batman Beyond',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8',
                    price: '$3.99',
                    series: 'Batman/Superman',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk',
                    price: '$4.99',
                    series: 'Batman/Superman Annual',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8',
                    price: '$5.99',
                    series: 'Batman: The Joker War Zone',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY',
                    price: '$6.99',
                    series: 'Batman: Three Jokers',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX',
                    price: '$4.99',
                    series: 'Batman: White Knight Presents: Harley Quinn',
                    type: 'comic book',
                },
                {
                    thumb:
                        'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq',
                    price: '$16.99',
                    series: 'Catwoman',
                    type: 'graphic novel',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
@import '@/styles/utilities';
@import '@/styles/vars';

.app{
    .jumbotron{
        height: 200px;
        background-image:url(../assets/jumbotron.jpg);
        background-position:top;
        background-size: cover;
    }
    .container{
        display: flex;
        flex-wrap: wrap;
    }
    position: relative;
    z-index: 3;
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