<template>
	<view class="container">
		<view class="box">
			<view class="bg"><image src="../../static/images/index/0817鉴定首页logo版.gif" mode=""></image></view>
			<view class="data-display">
				<image class="data-bg" src="../../static/images/index/数据背景@2x.png" mode=""></image>
				<view class="data-display-one">
					<image src="../../static/images/index/正六边形@2x.png" mode=""></image>
					<text>
						已鉴定
						<text class="number">1236</text>
						次
					</text>
				</view>
				<view class="data-display-one">
					<image src="../../static/images/index/正六边形@2x.png" mode=""></image>
					<text>
						假货市场占有率
						<text class="number">9.38%</text>
					</text>
				</view>
				<view class="data-display-two">
					<navigator url="../questions/questions">鉴定流程及常见问题</navigator>
					<image src="../../static/images/index/矩形2037@2x.png" mode=""></image>
				</view>
			</view>
			<view class="zm">
				<image src="../../static/images/index/字母bg@2x.png" mode=""></image>
				<view class="gn">
					<image src="../../static/images/index/专业鉴定@2x.png" mode=""></image>
					<image src="../../static/images/index/免费鉴定@2x.png" mode=""></image>
				</view>
				<view class="search">
					<input type="text" value="" placeholder="请输入您的六位鉴定ID" />
					<image class="input-image" src="../../static/images/index/输入框@2x.png" mode=""></image>
					<image class="search-image" src="../../static/images/index/查询按钮@2x.png" mode=""></image>
				</view>
			</view>
		</view>
		<view class="lists">
			<view class="item">
				<image class="left-image" src="../../static/images/index/IMG_8859@2x.png" mode=""></image>
				<view class="item-right">
					<view class="top">
						<text>Air Jordan</text>
						<view>
							<image src="../../static/images/index/时间(3)@2x.png" mode=""></image>
							<text>2018-02-04</text>
						</view>
					</view>
					<view class="center"><text>鉴定为真</text></view>
					<view class="bottom">
						<text>
							免费鉴定结果仅供参考, 如有疑问请进行
							<text class="zy">专业鉴定</text>
						</text>
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
export default {
	data() {
		return {};
	},
	onLoad() {},
	methods: {}
};
</script>

<style lang="scss">
.box {
	position: relative;
}
.bg {
	image {
		width: 750rpx;
		height: 700rpx;
	}
}
.data-display {
	position: absolute;
	top: 530rpx;
	left: 0;
	right: 0;
	margin: 0 auto;
	width: 726rpx;
	padding-left: 62rpx;
	padding-top: 52rpx;
	z-index: 2;
	.data-bg {
		width: 726rpx;
		height: 264rpx;
		position: absolute;
		left: 0;
		top: 0;
		z-index: 0;
	}
	.data-display-one {
		position: relative;
		z-index: 1;
		image {
			width: 22rpx;
			height: 24rpx;
			margin-right: 16rpx;
		}
		.number {
			font-size: 36rpx;
			color: #5e95f4;
			font-weight: bold;
		}
		&:nth-of-type(2) {
			margin-top: 20rpx;
			.number {
				color: #282828;
			}
		}
	}
	.data-display-two {
		display: flex;
		align-items: center;
		justify-content: flex-end;
		position: relative;
		z-index: 1;
		font-size: 24rpx;
		color: #5e95f4;
		margin-top: 10rpx;
		text-align: right;
		padding-right: 76rpx;
		image {
			width: 10rpx;
			height: 18rpx;
			margin-left: 16rpx;
		}
	}
}
.zm {
	position: absolute;
	left: 0;
	right: 0;
	top: 678rpx;
	width: 750rpx;
	margin: 0 auto;
	z-index: 1;
	image {
		width: 750rpx;
		height: 426rpx;
	}
	.gn {
		margin-top: 44rpx;
		position: absolute;
		left: 0;
		top: 98rpx;
		text-align: center;
		width: 100%;
		image {
			width: 348rpx;
			height: 98rpx;
		}
	}
	.search {
		position: absolute;
		left: 0;
		top: 250rpx;
		input,
		image {
			position: absolute;
			top: 0;
		}
		input {
			padding-left: 80rpx;
			z-index: 2;
			lighting-color: 98rpx;
		}
		.input-image,
		input {
			width: 606rpx;
			height: 98rpx;
			left: 28rpx;
		}
		.search-image {
			width: 170rpx;
			height: 98rpx;
			left: 562rpx;
		}
	}
}
.lists {
	margin-top: 400rpx;
	padding-bottom: 24rpx;
	.item {
		display: flex;
		width: 690rpx;
		height: 180rpx;
		border-radius: 20rpx;
		background-color: #ffffff;
		margin: 0 auto;
		padding: 24rpx;
	}
	.left-image {
		width: 132rpx;
		height: 132rpx;
		border-radius: 10rpx;
	}
	.item-right {
		margin-left: 24rpx;
		.top {
			display: flex;
			justify-content: space-between;
			text {
				&:nth-of-type(1) {
					font-size: 28rpx;
				}
				&:nth-of-type(2) {
					font-size: 24rpx;
					color: #858585;
				}
			}
			image {
				width: 22rpx;
				height: 22rpx;
				vertical-align: top;
				margin-top: 9rpx;
				margin-right: 10rpx;
			}
		}
		.center {
			margin-top: 6rpx;
			text {
				font-size: 22rpx;
				color: #7f5b3c;
				display: inline-block;
				background-color: #e6dcb5;
				padding: 5rpx;
				border-radius: 5rpx;
			}
		}
		.bottom {
			margin-top: 14rpx;
			text {
				font-size: 22rpx;
				color: #282828;
			}
			.zy {
				color: #5e95f4;
			}
		}
	}
}
</style>
