<template>
    <div class="imgs-group">
        <div class="img">
            <img :src="item.imgurl">
        </div>
        <div class="text" v-text="item.title"></div>
    </div>
</template>

<script>
    export default {
        name: 'ImgsSide',
        data() {
            return {

            }
        },
        props: ["item"]
    }
</script>

<style scoped>
    .imgs-group {
        display: block;
        width: calc((1020px - 110px) / 2);
        height: 317px;
        float: left;
    }
    .imgs-group::before {
        position: absolute;
        content: '';
        display: block;
        width: calc((1020px - 110px) / 2);
        height: 317px;
    }
    .imgs-group .img {
        width: 100%;
    }
    .imgs-group .img img {
        width: 100%;
    }
    .imgs-group .text{
        text-align: center;
        margin-top: 30px;
        font-size: 23px;
    }
</style>
