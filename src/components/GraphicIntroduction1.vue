<template>
    <div id="GraphicIntroduction" class="container" :style="{'height': 340*(dataList.length)/2 + 228+'px'}">
        <div class="content">
            <div class="text-group">
                <p class="text t1">Where will the mastermind take place?</p>
                <p class="text t2">Zakynthos GREECE</p>
                <p class="text t2">September 15th - 19th 2018</p>
                <p class="text t1">Check out our 6000 Sq ft Private Villa</p>
            </div>
            <Imgs-side v-for="(item,index) in dataList" :key="index" class="imgs-side " :class="{'odd': index%2 !== 0}" :item="item"></Imgs-side>
        </div>
    </div>
</template>

<script>
    import ImgsSide from './ImgsSide1'

    export default {
        name: 'GraphicIntroduction',
        data () {
            return {
                dataList: [
                    {
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/47/9198a167f611e88f7d8f6a0693716a/010-_2_.jpg',
                        title: 'The Infinity Pool'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/c0/7fcf9067ea11e88e4095e70afff17d/007-_1_.jpg',
                        title: 'The Breathtaking View from the pool'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/7a/a36881689711e8b6c34df9023e2cdf/013-_1_.jpg',
                        title: 'The View to the Tree House & Tennis Court'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/91/cef510689711e8aebbb5027d42f117/048.jpg',
                        title: 'The View from the Barbecue'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/b2/888fb067f611e88d9ca3c57d0f1fab/040-_1_.jpg',
                        title: 'Where our mastermind is going to be hosted'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/e2/7515e167f611e89493673c7c6bcc4e/003-_1_.jpg',
                        title: 'Sunset View from one of the Bedrooms :)'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/32/44b5d0696411e89d364fe9c13c5996/004.jpg',
                        title: 'One of the bedrooms & bathroom'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/42/1ad161696411e8a9d20bb4286b05c6/006.jpg',
                        title: 'Barbecue with a view'
                    }
                ]
            }
        },
        components: {
            ImgsSide
        }
    }
</script>

<style scoped>
    #GraphicIntroduction {
        clear: both;
    }
    .text-group {
        width: 100%
    }
    .text-group p {
        text-align: center;
    }
    .text {
        font-weight: 700;
        color: #2D2D2D;
    }
    .t1:first-child {
        font-size: 38px;
        margin-top: 0;
        margin-bottom: 25px;
    }
    .t1:last-child {
        font-size: 38px;
        margin-top: 25px;
        margin-bottom: 0;
    }
    .t2 {
        font-size: 26px;
        margin: 0;
    }
    .imgs-side {
        margin: 15px 0px;
    }
    .odd {
        margin-left: 110px;
    }
</style>
