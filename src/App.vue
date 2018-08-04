<template>
	<div id="app">
		<Header></Header>
		<Banner></Banner>
		<Lines></Lines>
		<Introduce></Introduce>
		<Lines></Lines>
		<Plain-text-block1></Plain-text-block1>
		<Lines></Lines>
		<Graphic-introduction></Graphic-introduction>
		<Lines></Lines>
		<Plain-text-block2></Plain-text-block2>
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
	import PlainTextBlock1 from "./components/PlainTextBlock";
	import PlainTextBlock2 from "./components/PlainTextBlock2";
	import GraphicIntroduction from "./components/GraphicIntroduction"

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
			Introduce,
			PlainTextBlock1,
			PlainTextBlock2,
			GraphicIntroduction
		}
	}
</script>

<style>
	* {
		font-family: "Montserrat", Helvetica, sans-serif;
	}
</style>