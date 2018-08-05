<template>
    <div id="GraphicIntroduction" class="container" :style="{'height': 317*(dataList.length)/2 + 228+'px'}">
        <div class="content">
            <p class="text t1">Who else is going to be there?</p>
            <div class="side">
                <div class="red"></div>
                <div class="black"></div>
            </div>
            <p class="text t2">An inspiring lineup of speakers with proven track records for success. Learn from the best and apply everything directly to your business.</p>
            <p class="text t3">Nick Peroni, Depesh Mandalia & me are going to be there physically</p>
        </div>
    </div>
</template>

<script>
    import ImgsSide from './ImgsSide2'

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
    .text {
        color: #2F2F2F;
        text-align: center;
    }
    .side {
        width: 150px;
        height: 5px;
        margin: 0 auto;
    }
    .side div {
        height: 100%;
        width: 50%;
        float: left;
    }
    .side div.red {
        background: #FF0036;
    }
    .side div.black {
        background: #2D2D2D;
    }
    .t1 {
        font-size: 44px;
        font-weight: 700;
        margin: 20px 0;
    }
    .t2 {
        font-size: 22px;
    }
    .t3 {
        font-size: 32px;
        font-weight: 700;
    }
</style>
