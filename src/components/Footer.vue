<template>
  <div class="section">
      <div class="container">
            <button>SIGN-UP NOW!</button>
            <nav> 
                <h3>FOLLOW US</h3>
                <img src="@/assets/footer-facebook.png" alt="">
                <img src="@/assets/footer-twitter.png" alt="">
                <img src="@/assets/footer-youtube.png" alt="">
                <img src="@/assets/footer-pinterest.png" alt="">
                <img src="@/assets/footer-periscope.png" alt="">
            </nav>
      </div>
  </div>
</template>

<script>
export default {
    name:'Footer',
}
</script>

<style scoped lang="scss">
@import'@/styles/vars';
@import '@/styles/utilities';
    .section{
        position: relative;
        background: $colorLightGrey;
        z-index: 3;
    }
    .container{
        padding: 20px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    button{
        padding: 10px;
        border:solid 1px $colorBlue;
        font-size: 16px;
        color:white;
        background: $colorLightGrey;
        cursor: pointer;
    }
    nav{
        display: flex;
        align-items: center;

        h3{
            color:$colorBlue;
            margin-right: 14px;
        }
        img{
            margin-left: 14px;
            widows: 20px;
            cursor: pointer;
        }
        
    }
    
    
</style>