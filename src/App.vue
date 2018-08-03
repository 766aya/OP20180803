<template>
	<div id="app">
		<Header></Header>
	</div>
</template>

<script>
	import Header from './components/header'
	export default {
		name: 'app',
		data() {
			return {
				msg: ''
			}
		},
		components: {
			Header
		}
	}
</script>

<style>

</style>