<template>
	<div id="banner" class="container">
		<p class="text t1">WELCOME TO THE 4th Edition of the</p>
		<p class="text t2">GREEK MASTERMIND</p>
		<p class="text t1">Zakynthos GREECE - Sep 15th - 19th 2018</p>
		<p class="text t3" style="margin-top: 30px;">Want all the details in a snap?</p>
		<p class="text t3">Click the button below & i will send you all the details</p>
		<Button></Button>
	</div>
</template>

<script>
	import Button from './banner-button'
	export default {
		name: 'banner',
		data() {
			return {
				
			}
		},
		components: {
			Button
		}
	}
</script>

<style scoped>
	#banner {
		height: 325px;
		background: url('../assets/007-_1_.jpg') no-repeat;
		background-attachment: fixed;
		background-position: top;
		background-size: 100% auto;
		padding: 60px 0px;
	}
	.text {
		text-align: center;
		margin: 0 auto;
		color: #FFFFFF;
	}
	.t1 {
		font-size: 24px;
	}
	.t2 {
		font-weight: 700;
		font-size: 56px;
	}
	.t3 {
		font-weight: 700;
		font-size: 24px;
	}
</style>