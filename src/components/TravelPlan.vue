<template>
	<div id="TravePlan" class="container">
		<div class="text-group content">
			<p class="t1">Mastermind Schedule</p>
			<p class="t2">September 15th - September 19th 2018</p>
			<p class="t2">Zakynthos GREECE</p>
		</div>
		<Travel-plan-item v-for="item in items" :item="item"></Travel-plan-item>
	</div>
</template>

<script>
	import TravelPlanItem from './TravelPlanItem'
	
	export default {
		name: 'TravePlan',
		data() {
			return {
				items: [
					{
						imgs: [
							'https://www.thegreekmastermind.com/hosted/images/c0/7fcf9067ea11e88e4095e70afff17d/007-_1_.jpg',
							'https://www.thegreekmastermind.com/hosted/images/6c/6defc067f611e88d9ca3c57d0f1fab/051-_2_.jpg'
						],
						title: 'Day 1',
						dates: 'Saturday September 15th 2018',
						desc: 'Arrival, meet & greet, networking drinks, private lunch & dinner at the villa',
						texts: [
							'You arrive any time and we hang out in the villa.',
							'The networking will be one of the top things you will love. ❤️',
							"Beers, drinks, food will be there for you so you won't have to stress out for that"
						]
					},{
						imgs: [
							'https://www.thegreekmastermind.com/hosted/images/47/9198a167f611e88f7d8f6a0693716a/010-_2_.jpg',
							'https://www.thegreekmastermind.com/hosted/images/7a/a36881689711e8b6c34df9023e2cdf/013-_1_.jpg',
							'https://www.thegreekmastermind.com/hosted/images/c6/24d9b1696411e88bfd172742d6de5d/041-_1_.jpg'
						],
						title: 'Day 2',
						dates: 'Sunday September 16th 2018',
						desc: 'The mastermind starts - Hot seats, networking, scaling to 7 & 8 figures',
						texts: [
							'The mastermind begins!',
							'Every single attendant will get my personal touch on his business. You can pick my brain for the whole 4 days we are going to be there & afterwards.',
							"But the hot seat is for you and you only! You will absolutely love this.",
							'After your "hot seat" you will have a strategic plan to grow 10X your online business.',
							'ROI is guaranteed.',
							'Structured presentations will be part of our day too.'
						]
					},{
						imgs: [
							'https://www.thegreekmastermind.com/hosted/images/42/1ad161696411e8a9d20bb4286b05c6/006.jpg',
							'https://www.thegreekmastermind.com/hosted/images/7e/520270696411e89ba03341b0e43f50/028-_1_.jpg'
						],
						title: 'Day 3',
						dates: 'Monday September 17th 2018',
						desc: 'The mastermind continues - Hot seats, networking, team building, systems & processes',
						texts: [
							'We keep masterminding, networking, eating, drinking, having fun!',
							'Being a room full of passionate entrepreneurs & exchanging ideas & planning for an amazing future is a thing you will absolutely love!'
						]
					},{
						imgs: [
							'https://www.thegreekmastermind.com/hosted/images/e2/7515e167f611e89493673c7c6bcc4e/003-_1_.jpg',
							'https://www.thegreekmastermind.com/hosted/images/6c/ab2911696511e88f57b9ad696df8dc/026.jpg',
							'https://www.thegreekmastermind.com/hosted/images/91/cef510689711e8aebbb5027d42f117/048.jpg',
							'https://www.thegreekmastermind.com/hosted/images/e0/18d510696411e8a9d20bb4286b05c6/044.jpg'
						],
						title: 'Day 4',
						dates: 'Tuesday September 18th 2018',
						desc: "Full day excursion on the island, boat, swimming with the turtles, party with the biggest DJ's",
						texts: [
							"Everyone's favourite day! <span>After hustling for 2+1 straight days, it's time to relax!</span>",
							'- In the morning we are going to <span>visit the famous Shipwreck beach. We have 2 full hours to swim with the turtles (if we see any), snorkeling, check out the actual shipwreck or enjoy the sun!</span>',
							'- We are also <span>visiting the Blue Caves, a secret beach that you have to see!</span>',
							'- In the afternoon, we check out the <span>breathtaking views of the shipwreck from above!</span> An experience to remember!',
							'- We will have an <span>awesome dinner at the best restaurant/coctail bar in the city.</span>',
							"- The party starts! We are going to make it in Laganas area, <span>where all the famous DJ's and the big parties are taking place! Time to party hard!</span>"
						]
					},{
						imgs: [
							'https://www.thegreekmastermind.com/hosted/images/03/71e790696511e8bc18d575ab232e4a/047-_1_.jpg',
							'https://www.thegreekmastermind.com/hosted/images/e2/7515e167f611e89493673c7c6bcc4e/003-_1_.jpg',
							'https://www.thegreekmastermind.com/hosted/images/1c/b72c60696511e8bc18d575ab232e4a/050-_1_.jpg'
						],
						title: 'Day 3',
						dates: 'Wednesday September 19th 2018',
						desc: 'We leave that beautiful villa (OPTIONAL : Mastermind continues in my city ATHENS )',
						texts: [
							'We have to leave the villa (or they will kick us out! LOL). <span>So you can either spend a few more days in the island or the transfer bus will drop you at the airport to catch your flight home.</span>',
							"There's a secret solution No 3!",
							"After hosting 3 events, i noticed a trend. <span style='font-weight:700;'>For half the room, it was the very first time that they visited Greece!</span>",
							'So they also wanted to see my city. Athens! <span>So i continued to be their host, taking them to the Acropolis, eating the famous Souvlaki & having fun!</span>',
							"So if you wanna check out Athens too after Zakynthos, you are more than welcome!"
						]
					}
				]
			}
		},
		components: {
			TravelPlanItem
		}
	}
</script>

<style scoped>
	.text-group {
		text-align: center;
		padding: 20px 0;
	}
	.t1 {
		font-size: 44px;
		font-weight: 700;
		color: #FF0036;
		margin: 0;
		margin-bottom: 15px;
	}
	.t2 {
		font-size: 34px;
		color: #2F2F2F;
		font-weight: 700;
		margin: 0;
	}
</style>