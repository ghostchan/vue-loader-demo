<template>
	<div>
		<h1>welcome Vue</h1>
		<h2 @click="change">{{msg}}</h2>
	</div>

</template>
<script>
	export default{
		data(){
			return {
				msg:'welcome Vue ^_^'
			}
		},
		methods:{
			change(){
				this.msg='wahaha'
			}
		}
	}
</script>
<style>
	body{
		background: #ccc
	}
</style>