<template>
	<div id="vedioBlock" class="container">
		<div class="title container">
			WATCH LAST YEAR'S HIGHLIGHT REEL
		</div>
		<div class="main container">
			<p class="t1">Undeniably Inspirational</p>
			<p class="t2">See what all the hype is about</p>
			<div class="vedio">
				<iframe width="700" height="394" src="https://www.youtube.com/embed/O5JX1Iosqkw" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
			</div>
			<Message-btn></Message-btn>
		</div>
	</div>
</template>

<script>
	import MessageBtn from './banner-button';
	
	export default {
		name: 'vedioBlock',
		data() {
			return {
				
			}
		},
		components: {
			MessageBtn
		}
	}
</script>

<style scoped>
	.title {
		height: 60px;
		line-height: 60px;
		text-align: center;
		font-size: 26px;
		font-weight: 700;
		color: #FFFFFF;
		background: #25405E;
	}
	.main {
		height: 800px;
		background: url('https://www.thegreekmastermind.com/hosted/images/cd/5c5770b53311e7bd442956307551d0/hero-bg.png') no-repeat;
		background-attachment: fixed;
		background-size: auto 100%;
	}
	.t1 {
		font-size: 44px;
		font-weight: 700;
		color: #FFFFFF;
		text-align: center;
		/*margin: 0;
		padding-top: 50px;*/
	}
	.t2 {
		font-size: 22px;
		color: #FFFFFF;
		text-align: center;
		margin: 0;
		padding-top: 10px;
	}
	.vedio {
		width: 700px;
		height: 394px;
		margin: 70px auto;
	}
</style>