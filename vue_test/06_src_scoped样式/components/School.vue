<template>
	<div class="demo">
		<h2 class="title">学校名称：{{name}}</h2>
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
		}
	}
</script>

<style scoped>
	.demo{
		background-color: skyblue;
	}
</style>