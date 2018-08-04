<template>
	<div id="app">
		<Header></Header>
		<Banner></Banner>
		<Lines></Lines>
		<Introduce></Introduce>
		<Lines></Lines>
		<Lines></Lines>
		<Lines></Lines>
		<Lines></Lines>
		<Lines></Lines>
		<Lines></Lines>
		<Lines></Lines>
	</div>
</template>

<script>
	import Header from './components/header'
	import Banner from './components/banner'
	import Lines from './components/LogoSegmentingLine'
	import Introduce from './components/introduce'
	
	export default {
		name: 'app',
		data() {
			return {
				msg: ''
			}
		},
		components: {
			Header,
			Banner,
			Lines,
			Introduce
		}
	}
</script>

<style>

</style>