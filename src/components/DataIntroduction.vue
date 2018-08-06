<template>
	<div id="DataIntroduction" class="container">
		<div class="content">
			<div class="box">
				<p class="t1">3</p>
				<div class="line"></div>
				<p class="t2">Events</p>
			</div>
			<div class="box">
				<p class="t1">42</p>
				<div class="line"></div>
				<p class="t2">Attendees</p>
			</div>
			<div class="box">
				<p class="t1">7</p>
				<div class="line"></div>
				<p class="t2">Live Speakers</p>
			</div>
			<div class="box">
				<p class="t1">42</p>
				<div class="line"></div>
				<p class="t2">Lives Changed</p>
			</div>
		</div>
	</div>
</template>

<script>
</script>

<style scoped>
	#DataIntroduction {
		margin: 10px auto;
		height: 260px;
		background: url('https://www.thegreekmastermind.com/hosted/images/b5/3ddd10248911e8a1fd43a680c11129/img2-min.jpg') no-repeat center center;
		background-size: 100% 100%;
	}
	.content {
		height: 260px;
	}
	.box {
		width: 25%;
		height: 140px;
		text-align: center;
		margin: 60px 0;
		float: left;
		color: #FFFFFF;
	}
	.line {
		display: block;
		width: 30px;
		height: 3px;
		background: #FFFFFF;
		margin: 20px auto;
	}
	.t1 {
		font-size: 60px;
		font-weight: 700;
		margin: 0;
	}
	.t2 {
		font-size: 18px;
		margin: 0;
	}
</style>