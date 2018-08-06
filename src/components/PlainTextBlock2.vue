<template>
    <div id="PlainTextBlock" class="container">
        <div class="content">
            <p class="text t1">"That sounds good but..."</p>
            <p class="text t2">Who is it for?</p>
            <ul>
                <li class="text iconfont icon-you">This is <span>NOT for newbies</span></li>
                <li class="text iconfont icon-you">This is for <span>high level entrepreneurs that have an established online business & looking to grow</span></li>
                <li class="text iconfont icon-true">We are <span>NOT going to teach you stuff you can find on Youtube</span></li>
                <li class="text iconfont icon-true">We are going to <span>focus on your biggest problems & at the end you will have the solutions to every single one of them.</span></li>
                <li class="text iconfont icon-true">You are going to <span>learn everything you need to scale to 7 & 8 figures, team building, systems & processes, fulfilment</span></li>
                <li class="text iconfont icon-true">You will have your own "hot seat". <span>It's a session 100% focused on you and your business.</span></li>
                <li class="text iconfont icon-true">The most important of all is that <span>every single person in the room is a 6, 7 or even 8 figure business owner.</span></li>
                <li class="text iconfont icon-true">You will <span>network with top level entrepreneurs from all around the world.</span></li>
                <li class="text iconfont icon-true">You will get your own strategic plan for business growth <span>& the results are 100% guaranteed.</span></li>
                <li class="text iconfont icon-true">It's the <span>only event that i offer 100% ROI guaranteed or i will issue a 100% refund. No questions asked.</span></li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'PlainTextBlock2',
        data() {
            return {
                
            }
        },
        mounted () {

        },
        methods: {
            
        }
    }
</script>

<style scoped>
    #PlainTextBlock {
        background: #416A96;
        padding: 15px 0;
    }
    p {
        text-align: center;
    }
    .text {
        color: #FFFFFF;
        margin: 0;
    }
    .t1 {
        font-size: 24px;
    }
    .t2 {
        font-weight: 700;
        font-size: 56px;
    }
    ul {
        list-style: none;
    }
    ul li {
        font-size: 22px;
        padding-bottom: 12px;
    }
    ul li::before {
        padding-right: 10px;
    }
    ul li span {
        font-weight: 700;
    }
</style>
