<template>
	<div id="app">
		<Header></Header>
		<Banner></Banner>
		<Lines></Lines>
		<Introduce></Introduce>
		<Lines></Lines>
		<Plain-text-block1></Plain-text-block1>
		<Lines></Lines>
		<Graphic-introduction1></Graphic-introduction1>
		<Plain-text-block2></Plain-text-block2>
		<Graphic-introduction2></Graphic-introduction2>
		<Data-introduction></Data-introduction>
		<Lines></Lines>
		<Plain-text-block3></Plain-text-block3>
		<Travel-plan></Travel-plan>
		<vedio-block></vedio-block>
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
	import PlainTextBlock3 from "./components/PlainTextBlock3";
	import GraphicIntroduction1 from "./components/GraphicIntroduction1"
	import GraphicIntroduction2 from "./components/GraphicIntroduction2"
	import DataIntroduction from "./components/DataIntroduction"
	import TravelPlan from "./components/TravelPlan"
	import vedioBlock from "./components/vedioBlock"
	
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
			PlainTextBlock3,
			GraphicIntroduction1,
			GraphicIntroduction2,
			DataIntroduction,
			TravelPlan,
			vedioBlock
		}
	}
</script>

<style>
	* {
		font-family: "Montserrat", Helvetica, sans-serif;
	}
</style>