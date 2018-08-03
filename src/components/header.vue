<template>
	<div id="header" class="container">
		<div class="content">
			<div id="logo" class="f-l">
				<img style="height: 100%; width: auto;" src="../assets/logo.png"/>
			</div>
			<div id="mail" class="f-l header-text iconfont icon-youxiang" v-text="mail"></div>
			<div id="telme" class="f-r header-text">
				<a href="javascript:;" class="iconfont icon-facebook" v-text="facebook" @click="callMe"></a>
			</div>
		</div>
	</div>
</template>

<script>
	
	
	export default {
		name: 'header',
		data () {
			return {
				mail: 'dimitris@dimitrisskiadas.com',
				facebook: 'FB Message Me'
			}
		},
		methods: {
			callMe() {
				window.alert('click call me!')
			}
		}
	}
</script>

<style scoped="scoped">
	#header {
		height: 85px;
		overflow: hidden;
		background: #FEFEFE;
	}
	.content{
		height: 85px;
	}
	#logo {
		height: 85px;
	}
	#mail {
		height: 35px;
		width: 250px;
		margin: 25px 0px;
		margin-left: 200px;
		line-height: 35px;
		font-size: 15px;
	}
	#mail:before {
		color: #FF0036;
		line-height: 35px;
	}
	.header-text {
		height: 35px;
		margin: 25px 0px;
		line-height: 35px;
		font-size: 15px;
	}
	.header-text a {
		color: #000000;
		text-decoration: none;
	}
	.header-text a:before {
		color: #25405E;
	}
</style>