<template>
	<div class="school">
		<h2>学校名称：{{name}}</h2>
		<h2>学校地址：{{address}}</h2>
	</div>
</template>

<script>
	export default {
		name:'School',
		data() {
			return {
				name:'岳阳市第13中学',
				address:'岳阳市奇家岭'
			}
		},
	}
</script>

<style>
	.school{
		background-color: gray;
	}
</style>