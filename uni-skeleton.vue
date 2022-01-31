<template>
	<view class="uni-skeleton">
		<h3 class="uni-skeleton-title" style="width: 38%;"></h3>
		<ul class="uni-skeleton-paragraph">
			<li></li>
			<li></li>
			<li style="width: 61%;"></li>
		</ul>
	</view>
</template>

<script>
	export default {
		name:"uni-skeleton",
		data() {
			return {
				
			};
		}
	}
</script>

<style scoped>
.uni-skeleton{
	width: 100%;
}
.uni-skeleton .uni-skeleton-title{
	height: 16px;
	margin-top: 16px;
	background: #f2f2f2;
}
.uni-skeleton .uni-skeleton-paragraph{
	margin: 0;
	padding: 6px 0 0 0;
}
.uni-skeleton .uni-skeleton-paragraph>li{
	width: 100%;
	margin: 16px 0 0 0;
	height: 16px;
	list-style: none;
	background: #f2f2f2;
}
</style>
