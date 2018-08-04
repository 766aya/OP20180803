<template>
	<div id="introduce" class="container">
		<div class="content">
			<div class="main">
				<p class="text t1">Hello, i am your host</p>
				<p class="text t2">Dimitris Skiadas</p>
				<div class="color-box">
					<div style="background: #E60901;"></div>
					<div style="background: #2D2D2D;"></div>
				</div>
				<ul class="longTextList">
					<li>-Worldwide public speaker, trainer & e-commerce expert.</li>
					<li>-Have helped 100+ entrepreneurs 1-on-1 to scale their business to 7 & 8 figures.</li>
					<li>-10,000+ people have watched my free trainings.</li>
					<li>-Hosted the first 3 events of the "Greek mastermind" in Santorini & Zakynthos (2017 & 2018)</li>
				</ul>
				<ul class="lowTextList">
					<li>Worldwide Public Speaker</li>
					<li>11 events, 3000+ people</li>
					<li>Trainer & GA expert</li>
					<li>10,000+ have watched my free trainings</li>
					<li>High end CRO consultant</li>
					<li>100+ Case Studies.</li>
				</ul>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'Introduce',
		data() {
			return {
				msg: ''
			}
		}
	}
</script>

<style scoped>
	#introduce {
		background: url('../assets/final111.png') no-repeat;
		background-size: 100% auto;
		height: 500px;
		overflow: hidden;
	}
	.content {
		height: 100%;
	}
	.main {
		width: 60%;
		height: 100%;
		float: right;
		padding: 10px 0px 0px 0px;
		color: #1f1f1f;
	}
	.longTextList {
		list-style: none;
		margin: 0;
		padding: 0;
		font-weight: 700;
	}
	.longTextList li {
		padding: 15px 0;
		font-size: 18px;
	}
	.color-box {
		width: 150px;
		height: 5px;
		margin-top: 15px;
	}
	.color-box div {
		height: 5px;
		float: left;
	}
	.color-box div:first-child {
		width: 60%;
	}
	.color-box div:last-child {
		width: 40%;
	}
	.text {
		padding: 0;
		margin: 0;
	}
	.t1 {
		font-size: 44px;
		font-weight: 700;
	}
	.t2 {
		font-size: 36px;
		font-weight: 700;
	}
	.lowTextList {
		list-style: none;

	}
	.lowTextList li {
		width: 50%;
		float: left;
		margin-top: 15px;
	}
</style>