<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view>
			<text class="title">{{title}}</text>
		</view>
	</view>
</template>

<script setup>
	const title = "Hello"
</script>

<style lang="scss" scoped>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		.logo {
			height: 200rpx;
			width: 200rpx;
			margin: 200rpx auto 50rpx auto;
		}
		.title {
			font-size: 36rpx;
			color: #8f8f94;
		}
	}
</style>
