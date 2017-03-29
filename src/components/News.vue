<template>
	<div>
		<h3>我是新闻</h3>
		<ul>
			<li v-for="(arr,index) in newsData">{{index}}:{{arr}}</li>
		</ul>
	</div>
</template>
<script>
export default {
	name:'news',
	data(){
		return {
			newsData:[111,222,333,444]
		}
	}
}
</script>