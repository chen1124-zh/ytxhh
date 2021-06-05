<template>
	<view class="content">
		<view class="">
			<van-search shape="round" background="#D81E06" :value="search" placeholder="请输入搜索关键词" />
		</view>
		<view class="">
			<swiper class="swiper" circular='true' indicator-dots='true'>
				<swiper-item >
					<view class="swiper-item uni-bg-red">
						<image src="../../static/default_head.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-green">
						<image src="../../static/default_head.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../static/default_head.jpg" mode=""></image>
					</view>
				</swiper-item>
			</swiper>
		</view>
		
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
		components:{
			
		},
		methods: {
			forceUpdate(){
			}
		}
	}
</script>
 
<style>
	
	.swiper{
		overflow: hidden;
		border-radius: 10rpx;
		margin: 20rpx;
	}
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
