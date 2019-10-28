<template>
	<view class="container">
		<view class="box">
			<view class="left">
				<image src="../../static/images/assessment/IMG_8859@2x.png" mode=""></image>
				<view class="font">鞋子</view>
			</view>
			<view class="right">
				<view class="top">
					<view class="text">实习鉴定师</view>
					<view class="shallow">鉴定师</view>
				</view>
				<view class="center"><view class="progress"></view></view>
				<view class="bottom">
					<view class="mn"><image src="../../static/images/assessment/模拟考试1@2x.png"></image>模拟考试</view>
					<view class="sj"><image src="../../static/images/assessment/升级@2x.png"></image>升级考试</view>
				</view>
			</view>
		</view>
		<view class="box">
			<view class="left">
				<image src="../../static/images/assessment/IMG_8859@2x.png" mode=""></image>
				<view class="font">鞋子</view>
			</view>
			<view class="right">
				<view class="top">
					<view class="text">鉴定师</view>
					<view class="shallow">高级鉴定师</view>
				</view>
				<view class="center"><view class="progress"></view></view>
				<view class="bottom">
					<view class="mn"><image src="../../static/images/assessment/模拟考试1@2x.png"></image>模拟考试</view>
					<view class="sj"><image src="../../static/images/assessment/升级@2x.png"></image>升级考试</view>
				</view>
			</view>
		</view>
		<view class="add">
			<text class="icon">+</text> 添加品牌
		</view>
	</view>
</template>

<script></script>

<style lang="scss">
.box {
	width: 690rpx;
	height: 180rpx;
	background-color: #ffffff;
	border-radius: 10rpx;
	margin: 18rpx auto;
	padding: 35rpx 35rpx 30rpx 35rpx;
	display: flex;
	justify-content: space-between;

	.left {
		image {
			width: 80rpx;
			height: 80rpx;
			box-shadow: 0rpx 4rpx 8rpx 0rpx 
				rgba(0, 0, 0, 0.1);
			border-radius: 40rpx;
		}
		.font {
			width: 60rpx;
			height: 30rpx;
			line-height: 30rpx;
			background-color: #e36cd9;
			border-radius: 15rpx;
			text-align: center;
			font-size: 20rpx;
			color: #ffffff;
			margin-top: 15rpx;
			margin-left: auto;
			margin-right: auto;
		}
	}
	.right {
		view {
			font-size: 22rpx;
			color: #4d4d4d;
		}
		.top {
			margin-bottom: 18rpx;
			justify-content: space-between;
			.shallow {
				color: #e9e9ee;
			}
			.text {
				color: #282828;
			}
		}
		.center {
			width: 516rpx;
			height: 16rpx;
			background-color: #eeeef3;
			border-radius: 8rpx;
			position: relative;
			overflow: hidden;
			.progress {
				position: absolute;
				left: 0;
				top: 0;
				height: 16rpx;
				width: 45%;
				border-radius: 8rpx;
				background-image: linear-gradient(90deg, #39b6f2 0%, #6a67f5 100%), linear-gradient(#e6dcb5, #e6dcb5);
			}
		}
		.top,
		.bottom {
			display: flex;
		}
		.bottom {
			margin-top: 24rpx;
			justify-content: flex-end;
			.mn,.sj {
				display: flex;
				align-items: cneter;
				image {
					width: 26rpx;
					height: 26rpx;
					margin-right: 12rpx;
				}
			}
			.sj {
				margin-left: 24rpx;
			}
		}
	}
}
.add {
	position: fixed;
	bottom: 90rpx;
	left: 0;
	right: 0;
	margin: 0 auto;
	width: 250rpx;
	height: 80rpx;
	line-height: 80rpx;
	text-align: center;
	background-color: #ffffff;
	border-radius: 40rpx;
	.icon {
		color: #cdcdcd;
		font-size: 36rpx;
		margin-right: 10rpx;
	}
}
</style>
