<template>
    <div id="PlainTextBlock" class="container">
        <div class="content">
            <p class="text t1">"OK, that's sounds awesome but..."</p>
            <p class="text t2">What does the mastermind include?</p>
            <ul>
                <li class="text iconfont icon-you">This mastermind includes everything besides your flights.</li>
                <li class="text iconfont icon-you">To be more specific, the fee includes : </li>
                <li class="text iconfont icon-true"><span>Transports from and to the airport</span></li>
                <li class="text iconfont icon-true"><span>5 days (4 nights) stay at the villa at your own bedroom and bathroom</span></li>
                <li class="text iconfont icon-true">Food ( 3 meals per day for all 5 days cooked by 2 famous private chefs. <span>Breakfast - Lunch - Dinner - Traditional Greek food cooked inside our villa every day</span></li>
                <li class="text iconfont icon-true"><span>Drinks, beers, wines, snacks, deserts are also included.</span></li>
                <li class="text iconfont icon-true"><span>Full day excursion with boat in the famous Shipwreck beach</span></li>
                <li class="text iconfont icon-true"><span>Swimming with the turtles</span></li>
                <li class="text iconfont icon-true"><span>Dinner in the most famous cocktail/restaurant</span>bar in the town</li>
                <li class="text iconfont icon-true"><span>Party (dance & drinks) at the famous Laganas where all the big DJ's</span>throw the biggest parties</li>
                <li class="text iconfont icon-true"><span>Your seat at the mastermind </span></li>
                <li class="text iconfont icon-true"><span>High level networking with high level entrepreneurs & training from top trainers as Nick Peroni & Depesh Mandalia</span></li>
                <li class="text iconfont icon-true"><span>The fee is $5,000</span> paid during the booking of your seat.</li>
                <li class="text iconfont icon-true">It's the only event that i give <span>100% ROI guaranteed</span> or i will issue a 100% refund. No questions asked.</li>
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
