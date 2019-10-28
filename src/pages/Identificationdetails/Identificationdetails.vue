<template>
	<view class="container">
		<view class="info">
			<view class="top">
				<view class="title">服务项目</view>
				<view class="img">
					<image src="../../static/fa/专业鉴定@2x.png" mode=""></image>
				</view>
				<view class="bj">
					保价
				</view>
				<view class="price">
					￥5000
				</view>
			</view>
			<view class="center">
				<view class="head">
					<image src="../../static/fa/组26@2x.png" mode=""></image>
				</view>
				<view class="userinfo">
					<view class="name">
						用户名称用户名称
					</view>
					<view class="bq">
						暂无标签
					</view>
				</view>
				<view class="jd">
					已鉴定 23 双
				</view>
			</view>
			<view class="bottom">
				<view class="tab">
					<image src="../../static/fa/个人主页2@2x.png" mode=""></image>
					<text>查看主页</text>
				</view>
				<view class="tab">
					<image src="../../static/fa/记录@2x.png" mode=""></image>
					<text>查看记录</text>
				</view>
				<view class="tab">
					<image src="../../static/fa/备注@2x.png" mode=""></image>
					<text>备注标签</text>
				</view>
			</view>
		</view>
		<view class="djd">
			<view class="top">
				<view class="title">
					<image src="../../static/待鉴定@2x.png" mode=""></image>
				</view>
				<image class="bjd-img" src="../../static/fa/技术支持2@2x.png" mode=""></image>
			</view>
			<view class="bottom">
				全球首创三人专业鉴定模式，为您的鉴定保驾护航
			</view>
		</view>
		<view class="tip">
			微信小程序：BAN装备鉴定，输入 <text class="text">756324</text> 查询原帖
		</view>
		<view class="content">
			<view class="title">
				Air Jordan
			</view>
			<view class="beizhu">
				备注信息备注信息备注信息
			</view>
			<view class="imgs">
				<view class="img-box">
					<view class="img">
						<image src="../../static/IMG_8859@3x.png" mode=""></image>
						<view class="mark">
							外观
						</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/IMG_8859@3x.png" mode=""></image>
						<view class="mark">
							外观
						</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/IMG_8859@3x.png" mode=""></image>
						<view class="mark">
							外观
						</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/IMG_8859@3x.png" mode=""></image>
						<view class="mark">
							外观
						</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/IMG_8859@3x.png" mode=""></image>
						<view class="mark">
							外观
						</view>
					</view>
				</view>
			</view>
		</view>
		<view class="button">
			开始鉴定
		</view>
	</view>
</template>

<script>
</script>

<style lang="scss">
	.info {
		width: 690rpx;
		height: 246rpx;
		background-color: #ffffff;
		border-radius: 10rpx;
		padding: 28rpx 28rpx 28rpx 38rpx;
		margin: 15rpx auto;
		.title {
			flex: 1;
			height: 25rpx;
			font-size: 26rpx;
			color: #393939;
			white-space: nowrap;
		}
		.img {
			image {
				width: 122rpx;
				height: 28rpx;
			}
		}
	}
	.top,.center,.bottom {
		display: flex;
		align-items: center;
	}
	.top {
		.bj {
			width: 70rpx;
			height: 32rpx;
			text-align: center;
			line-height: 30rpx;
			background-color: #ff2929;
			border-radius: 16rpx;
			border: solid 1rpx #f32828;
			font-size: 24rpx;
			color: #ffffff;
			margin-left: 26rpx;
		}
		margin-bottom: 30rpx;
		.price {
			margin-left: 10rpx;
		}
		image {
			margin-left: 200rpx;
		}
	}
	.center {
		margin-bottom: 22rpx;
		.head {
			image {
				width: 68rpx;
				height: 68rpx;
			}
		}
		.userinfo {
			margin-left: 22rpx;
			.name {
				font-size: 26rpx;
				color: #282828;
			}
			.bq {
				margin-top: 10rpx;
				color: #858585;
				font-size: 20rpx;
			}
		}
		.jd {
			flex: 1;
			text-align: right;
			margin-right: 10rpx;
		}
	}
	.bottom {
		.tab {
			display: flex;
			align-items: center;
			margin-left: 99rpx;
			image {
				margin-right: 14rpx;
			}
			text {
				font-size: 24rpx;
				color: #858585;
			}
			&:nth-of-type(1) {
				margin-left: 0;
				image {
					width: 38rpx;
					height: 31rpx;
				}
			}
			&:nth-of-type(2) {
				image {
					width: 32rpx;
					height: 34rpx;
				}
			}
			&:nth-of-type(3) {
				image {
					width: 28rpx;
					height: 32rpx;
				}
			}
		}
	}
	.djd {
		background-color: #FFFFFF;
		.title {
			image {
				width: 125rpx;
				height: 40rpx;
			}
		}
		.bjd-img {
			width: 172rpx;
			height: 60rpx;
		}
		.bottom {
			font-size: 24rpx;
			color: #282828;
		}
	}
	.tip {
		font-size: 22rpx;
		color: #989898;
		height: 50rpx;
		line-height: 50rpx;
		background-color: #eef1f4;
		text-align: center;
		text {
			display: inline-block;
			width: 90rpx;
			height: 26rpx;
			line-height: 26rpx;
			text-align: center;
			background-color: #989898;
			border-radius: 8rpx;
			font-size: 22rpx;
			color: #ffffff;
		}
	}
	.imgs {
		display: flex;
		flex-wrap: wrap;
		text-align: center;
		padding-left: 28rpx;
		padding-right: 28rpx;
		.img-box {			
			font-size: 22rpx;
			color: #ffffff;
			width: 25%;
			display: inline-block;
			.img {
				position: relative;
				height: 150rpx;
					width: 150rpx;
				image {
					width: 150rpx;
					height: 150rpx;
					background-color: #f3f0ef;
					border-radius: 8rpx;
					position: absolute;
					left: 0;
					top: 0;
				}
				.mark {
					position: absolute;
					bottom: 0;
					left: 0;
					height: 40%;
					background-color: rgba($color: #000000, $alpha: 0.5);
					z-index: 3;
					width: 100%;
					display: flex;
					align-items: center;
					justify-content: center;
					color: #FFFFFF;
					font-size: 22rpx;
				}
			}
		}
	}
	.button {
		position: fixed;
		left: 0;
		right: 0;
		bottom: 50rpx;
		width: 250rpx;
		height: 80rpx;
		line-height: 80rpx;
		text-align: center;
		margin: 0 auto;
		background-image: linear-gradient(-90deg, 
			#738af9 0%, 
			#799bf5 45%, 
			#7eabf1 100%), 
		linear-gradient(
			#5e95f4, 
			#5e95f4);
		background-blend-mode: normal, 
			normal;
		box-shadow: 0rpx 4rpx 10rpx 0rpx 
			rgba(0, 0, 0, 0.2);
		border-radius: 40rpx;
		opacity: 0.9;
		font-size: 28rpx;
		color: #ffffff;
	}
</style>
