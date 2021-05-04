<template>
  <header>
      <div class="container">
        <a href="#"><img src="../assets/dc-logo.png" alt=""></a>
        <nav>
            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a :class="{active:link.current}" :href="link.url">{{link.text}}</a>
                </li>
            </ul>
        </nav>
      </div> 
  </header>
</template>

<script>
export default {
    name:'Header',
    data(){
        return{
            links:[
                {
                    text:'CHARACTERS',
                    url:'/CHARACTERS',
                    current:true,
                },
                {
                    text:'COMICS',
                    url:'/COMICS',
                    current:false,
                },
                {
                    text:'MOVIES',
                    url:'/MOVIES',
                    current:false,
                },
                {
                    text:'TV',
                    url:'/TV',
                    current:false,
                },
                {
                    text:'GAMES',
                    url:'/GAMES',
                    current:false,
                },
                {
                    text:'VIDEOS',
                    url:'/VIDEOS',
                    current:false,
                },
                {
                    text:'FANS',
                    url:'/FANS',
                    current:false,
                },
                {
                    text:'NEWS',
                    url:'/NEWS',
                    current:false,
                },
                {
                    text:'SHOP',
                    url:'/SHOP',
                    current:false,
                },
            ]
        }
    },
}
</script>

<style scoped>
    .container{
        height: 100px;
        width: 80%;
        margin:0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    img{
        width: 50px;
    }
    ul{
        display: flex;
        flex-direction: row;
    }
    
    li{
        list-style: none;
        margin:0 10px;
        line-height: 100px;
        
    }
    .active{
        border-bottom: 4px solid #0282f9;
        color:#0282f9;
    }
    a{
        text-decoration: none;
        color:#1c1c1c;
        font-size: 16px;
        display: flex;
    }
</style>