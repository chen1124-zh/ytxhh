<template>
	<view>
		<view class="user">
			<!-- <image :src="user.portrait||'../../pagesA/static/default_head.jpg'" mode=""></image> -->
			<view class="userName">
				{{user.name||'未登录'}}
			</view>
		</view>
		<van-cell-group>
		  <van-cell title="设置" icon="setting-o" is-link/>
		</van-cell-group>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				user:{
					name:'',
					portrait:''
				}
			};
		},
		onShow() {
			this.appLoginWx()
		},
		methods:{
			appLoginWx(){
				
			}
		}
	}
</script>

<style lang="scss">
	.user{
		display: flex;
		align-items: center;
		padding: 20rpx 0;
		border-bottom: 1rpx solid #999;
		image{
			width: 150rpx;
			height: 150rpx;
			border-radius: 50%;
			margin-left: 50rpx;
		}
		.userName{
			margin-left: 30rpx;
		}
	}
</style>
 