<template>
    <div class="box">
        <img :src="details.thumb" alt="">
        <p>{{details.series}}</p>
    </div>
</template>

<script>
export default {
    name:'Card',
    props:['details'],
}
</script>

<style lang="scss">
    .box{
        width: calc(100%/6);
        height: inherit;
        padding: 20px;
        img{
            width: 100%;
        }
        p{
            text-transform: uppercase;
            color: white;
            padding: 10px 0;
        }

    }
</style>