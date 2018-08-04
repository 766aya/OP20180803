<template>
	<div class="container line">
		<div class="content">
            <img class="img" src="../assets/logo.png">
            <img class="img" src="../assets/logo.png">
            <img class="img" src="../assets/logo.png">
            <img class="img" src="../assets/logo.png">
            <img class="img" src="../assets/logo.png">
        </div>
	</div>
</template>

<script>
	export default {
		name: 'LogoSegmentingLine',
		data() {
			return {
				msg: ''
			}
		}
	}
</script>

<style scoped>
    .line {
        margin: 10px 0px;
        height: 70px;
    }
    .img {
        height: 70px;
        text-align: center;
        float: left;
    }
</style>