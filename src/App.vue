<template>
	<div id="app">
		<Header></Header>
		<Banner></Banner>
		<Lines></Lines>
		<Introduce></Introduce>
		<Lines></Lines>
		<Plain-text-block></Plain-text-block>
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
	import PlainTextBlock from "./components/PlainTextBlock";

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
	* {
		font-family: "Montserrat", Helvetica, sans-serif;
	}
</style>