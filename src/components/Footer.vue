<template>
  <div class="section">
      <div class="container">
            <button>SIGN-UP NOW!</button>
            <nav> loghi</nav>
      </div>
  </div>
</template>

<script>
export default {
    name:'Footer',
}
</script>

<style scoped>
    .section{
        background: #303030;
    }
    .container{
        width: 80%;
        margin: 0 auto;
        padding: 20px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    button{
        padding: 10px;
        border:solid 1px #0282f9;
        font-size: 16px;
        color:white;
        background: #303030;
    }
    
</style>