<template>
  <header>
      <div class="container">
        <a href="#"><img src="../assets/dc-logo.png" alt=""></a>
        <nav>
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </nav>
      </div> 
  </header>
</template>

<script>
export default {
    name:'Header',
}
</script>

<style scoped>
    .container{
        width: 80%;
        margin:0 auto;
        padding: 20px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    img{
        width: 50px;
    }
    li{
        list-style: none;
        display: inline;
        margin:0 10px;
    }
    a{
        text-decoration: none;
        color:#1c1c1c;
        font-size: 16px;
    }
</style>