<template>
	<view class="login-wrap">
		<image class="wel-logo" src="https://www.easyicon.net/api/resizeApi.php?id=1194607&size=128"></image>
		<view>
			<view>
				<button class="wel-btn" @click="login">新用户注册</button>
			</view>
			<view>
				<button class="wel-btn" @click="login">登录</button>
			</view>
			<view class="look">
				先逛逛
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			login () {
				uni.switchTab({
					url: '/pages/tabBar/API/API'
				})
			}
		}
	}
</script>

<style scoped>
	.login-wrap {
		height: 100%;
		background: url(https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=2409531235,104520390&fm=26&gp=0.jpg) no-repeat;
		background-size: cover;
		overflow: hidden;
	}
	
	.wel-logo {
		width: 200rpx;
		height: 200rpx;
		margin: 100rpx auto 0;
		display: block;
	}
	
	.look {
		color: white;
	}
	
	.wel-btn {
		width: 630rpx;
	}
	
</style>
