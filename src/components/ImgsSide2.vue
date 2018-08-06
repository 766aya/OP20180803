<template>
    <div class="imgs-group">
        <div class="img">
            <img :src="item.imgurl">
        </div>
        <div class="text-title" v-text="item.title"></div>
        <div class="text-desc" v-text="item.desc"></div>
    </div>
</template>

<script>
    export default {
        name: 'ImgsSide2',
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
        width: 310px;
        /*height: 317px;*/
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
        width: 310px;
        height: 310px;
        overflow: hidden;
    }
    .imgs-group .img img {
        width: 100%;
    }
    .imgs-group .text-title{
        text-align: center;
        margin-top: 30px;
        font-size: 23px;
        font-weight: 700;
    }
    .imgs-group .text-desc{
        text-align: center;
        font-size: 23px;
    }
</style>
