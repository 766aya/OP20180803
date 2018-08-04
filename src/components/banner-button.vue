<template>
	<div class="button" @click="btn">
		<p class="iconfont icon-xiaoxi">Send to Messanger</p>
	</div>
</template>

<script>
	export default {
		name: 'Banner-button',
		data() {
			return {
				
			}
		},
        methods: {
            btn() {

            }
        }
	}
</script>

<style scoped>
    .button {
        height: 40px;
        max-width: 180px;
        background-color: #FFFFFF;
        border-radius: 5px;
        margin: 25px auto;
        cursor: pointer;
    }
    .button p {
        padding: 0;
        margin: 0;
        text-align: center;
        color: #0084ff;
        line-height: 40px;
        font-family: sans-serif;
        font-size: 15px;
    }
    .button p::selection {
        background: none;
    }
</style>