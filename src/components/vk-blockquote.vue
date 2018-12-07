<template>
	<div class="vk-blockquote">
		<img src="../../img/quote.png" class="vk-blockquote-icon">
		<blockquote>{{text}}</blockquote>
	</div>
</template>

<script>
    export default {
        name: "vk-blockquote",
	    props: ['text']
    }
</script>

<style scoped>
	.vk-blockquote {
		display: flex;
		flex-direction: column;
		justify-content: flex-start;
		align-items: flex-start;
		
		padding-left: 15px;
		border-left: 1px solid #ccc;
		margin-bottom: 30px;
	}
	
	.vk-blockquote-icon {
		width: 30px;
		height: 30px;
	}
</style>