<template>
	<div id="TravelPlanItem" class="container">
		<div class="content grid-container">
			<div class="box1">
				<img v-for="url in item.imgs" :src="url"/>
			</div>
			<div class="box2">
				<p class="text t1" v-text="item.title"></p>
				<p class="text t2" v-text="item.dates"></p>
				<p class="text t3" v-text="item.desc"></p>
				<div style="width: 125px; height: 5px; display: grid; grid-template-columns: 40% 60%; margin-top: 20px;">
					<div style="background: #FF0036; height: 100%;"></div>
					<div style="background: #25405E; height: 100%;"></div>
				</div>
				<ul class="t-list">
					<li v-for="text in item.texts" v-html="text" class="t4"></li>
				</ul>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'TravelPlanItem',
		data() {
			return {
				
			}
		},
		props: ["item"]
	}
</script>

<style scoped>
	#TravelPlanItem {
		margin: 30px auto;
	}
	.grid-container {
		display: grid;
		grid-template-columns: 30% 70%;
		border: #E1E1E1 solid 10px;
	}
	.box1 {
		
	}
	.box1 img {
		width: calc(100% - 20px);
		margin: 10px;
	}
	.box2 {
		padding: 15px 10px 0px 10px;
	}
	.text {
		margin: 0;
	}
	.t1 {
		font-size: 26px;
		font-weight: 700;
	}
	.t2 {
		font-size: 26px;
		margin: 10px 0;
	}
	.t3 {
		font-size: 20px;
	}
	.t4 {
		font-size: 16px;
		margin: 0;
		padding: 20px 0;
	}
	span {
		
	}
	.t-list {
		list-style: none;
		margin-top: 10px;
		padding: 0;
	}
</style>