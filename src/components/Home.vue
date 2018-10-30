<template>
	<div id="home">
		<h1>{{msg}}</h1>
		<button @click="run">执行run方法</button>
	</div>
</template>

<script>
	export default{
		data(){
			return{
				msg:'我是Home组件'
			}
		},
		methods:{
			run(){
				alert(this.msg)
			}
		}
	}
</script>

<style lang="scss" scoped>
/*scoped: css局部作用域*/
	h1{ color: red;}
</style>