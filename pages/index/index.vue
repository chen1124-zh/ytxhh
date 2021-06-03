<template>
	<view class="content">
		<view class="">
			<van-search shape="round" background="#D81E06" :value="search" placeholder="请输入搜索关键词" />
		</view>
		<view class="">
			
		</view>
		<!-- <image class="logo" src="/static/logo.png"></image>
		<view class="text-area">
			<text class="title">{{title}}</text>
		</view> -->
	</view>
</template>

<script>
	export default {
		data() {
			return {
				search: ''
			}
		},
		onLoad() {

		},
		methods: {
			forceUpdate(){
				console.log(123)
			}
		}
	}
</script>
 
<style>
	/* .content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	} */
</style>
