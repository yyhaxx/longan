<template>
	<div class="index">
		{{name}}
	</div>
</template>

<script>
	export default{
		name: 'index',
		data () {
			return {
				name: 'index'
			}
		}
	}
</script>

<style scoped lang="less">
	@black: #000;
	.index{
		background: @black;
	}
</style>
