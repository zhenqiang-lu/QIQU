<template>
	<view class="login-wrap">
		<view class="login-hello">你好</view>
		<view>欢迎来到骑趣</view>
		<view>
			<view>
				<input type="text">
			</view>
			<view>
				<input type="text">
			</view>
			<view>
				<button @click="login">登录</button>
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
	}
</style>
