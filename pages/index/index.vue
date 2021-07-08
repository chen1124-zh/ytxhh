<template>
	<view class="content">
		<view class="">
			<van-search shape="round" background="#D81E06" :value="search" placeholder="请输入搜索关键词" />
		</view>
		<view class="">
			<!-- <swiper class="swiper" circular='true' indicator-dots='true'> -->
				<!-- <swiper-item >
					<view class="swiper-item uni-bg-red">
						<image src="../../pagesA/static/hryg/h1.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-green">
						<image src="../../pagesA/static/hryg/h2.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../pagesA/static/hryg/h3.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../pagesA/static/hryg/h8.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../pagesA/static/hryg/h4.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../pagesA/static/hryg/h5.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../pagesA/static/hryg/h6.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../pagesA/static/hryg/h7.jpg" mode=""></image>
					</view>
				</swiper-item>
				<swiper-item >
					<view class="swiper-item uni-bg-blue">
						<image src="../../pagesA/static/hryg/h7.jpg" mode=""></image>
					</view>
				</swiper-item>
			</swiper> -->
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
	
</style>
