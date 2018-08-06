<template>
    <div id="PlainTextBlock" class="container">
        <div class="content">
            <p class="text t1">What is the</p>
            <p class="text t2">GREEK MASTERMIND?</p>
            <ul>
                <li class="text iconfont icon-you">We gather 2 times per year in a beautiful Greek island (Zakynthos for 2018)</li>
                <li class="text iconfont icon-you">It's a <span>high end private meet up of entrepreneurs</span> from around the world</li>
                <li class="text iconfont icon-true">Its a <span>full 5 days of high level networking and private meet ups</span></li>
                <li class="text iconfont icon-true">The mastermind is held in <span>a private 6000 sq foot villa</span> in Zakynthos Greek island</li>
                <li class="text iconfont icon-true">We have 2 famous private Greek chef cooking for us delicious traditional Greek food 3 times per day</li>
                <li class="text iconfont icon-true"><span>You have your own private bedroom & bathroom</span>along with all amenities</li>
                <li class="text iconfont icon-true"><span>Drinks, beers, wine, snacks</span> are also included</li>
                <li class="text iconfont icon-true"><span>Transfers from and to the airport </span></li>
                <li class="text iconfont icon-true">Full day <code>excursion</code> with private boat <span>in the famous Shipwreck beach</span></li>
                <li class="text iconfont icon-true">Swimming with the turtles</li>
                <li class="text iconfont icon-true"><span>Private dinner dinner in the most famous cocktail bar/restaurant</span></li>
                <li class="text iconfont icon-true"><span>Party at the famous Laganas where all the famous DJ's play and parties</span> take place</li>
                <li class="text iconfont icon-true">Top level e-com entrepreneurs<span>( Nick Peroni, Depesh Mandalia, Mohamed Ali Aguel & more) will teach us high end strategies for growth</span></li>
                <li class="text iconfont icon-true">You will get <span>your own strategic plan for business growth & the results are 100% guaranteed.</span></li>
                <li class="text iconfont icon-true">It's the only event that i give <span>100% ROI guaranteed or i will issue a 100% refund. </span></li>
                <li class="text iconfont icon-true">No questions asked.</li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'PlainTextBlock',
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
    p {
        text-align: center;
    }
    .text {
        color: #2D2D2D;
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
