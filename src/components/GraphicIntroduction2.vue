<template>
    <div id="GraphicIntroduction" class="container">
        <div class="content">
            <p class="text t1">Who else is going to be there?</p>
            <div class="side">
                <div class="red"></div>
                <div class="black"></div>
            </div>
            <p class="text t2">An inspiring lineup of speakers with proven track records for success. Learn from the best and apply everything directly to your business.</p>
            <p class="text t3">Nick Peroni, Depesh Mandalia &amp; me are going to be there physically</p>
        </div>
        <div class="content">
        	<Imgs-side v-for="(item, index) in dataList1" :item="item" :class="{'m30': index!=0}"></Imgs-side>
        </div>
        <div class="content" style="clear: both; height: 1px;"></div>
        <div class="content" style="margin-top: 20px;">
            <p class="text t3">Thomas Bartke, Mo Ali Aguel and John Hutchison will be with us digitally</p>
        </div>
        <div class="content">
        	<Imgs-side v-for="(item, index) in dataList2" :item="item" :class="{'m30': index!=0}"></Imgs-side>
        </div>
        <div class="content" style="clear: both; height: 1px;"></div>
    </div>
</template>

<script>
    import ImgsSide from './ImgsSide2'

    export default {
        name: 'GraphicIntroduction2',
        data () {
            return {
                dataList1: [
                    {
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/77/9cd3f0680211e8aa8e9156f320797b/12794561_10208289750178230_8719256171907727336_n.jpg',
                        title: 'Dimitris Skiadas',
                        desc: 'Conversion Masters'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/74/db049067f111e88b5aef3bb36cf0cf/22520173_10101864494335589_3073692298959868496_o.jpg',
                        title: 'Nick Peroni',
                        desc: 'Ecom Empires'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/bf/114f608d2111e893c529b7733381bd/23116717_10155650172350498_4324371780502520801_o.jpg',
                        title: 'Depesh Mandalia',
                        desc: 'FB Ads Experts Academy'
                    }
                ],
                dataList2: [
                    {
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/cf/bd025067f111e8bea339625abaf3a0/20863387_10211686991803259_2241106883902257054_o.jpg',
                        title: 'Thomas Bartke',
                        desc: 'Trackify'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/be/8226a067f111e88b5aef3bb36cf0cf/26220618_10159725752960177_2115431594955615276_o.jpg',
                        title: 'Mohamed Ali Aguel',
                        desc: 'Always Listen To Mo'
                    },{
                        imgurl: 'https://www.thegreekmastermind.com/hosted/images/dc/ee3ca067f111e8a0cec76bf24cc2c2/21056104_1882582312061654_8315331212507508659_o.jpg',
                        title: 'John Hutchison',
                        desc: 'Conversion Secrets'
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
    .m30 {
    	margin-left: 30px;
    }
</style>
