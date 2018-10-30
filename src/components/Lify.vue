<template>
	<div>{{msg}}</div>
</template>

<script>
	export default{
		data(){
			return{
				msg:'我是生命周期函数'
			}
		},
		beforeMount(){
			console.log('在挂载开始之前被调用')
		}
	}
</script>

<style>
</style>