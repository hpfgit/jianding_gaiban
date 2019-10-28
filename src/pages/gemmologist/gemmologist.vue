<template>
	<view class="container">
		<view class="FreeAdmission">
			<view class="custom-title">我的鉴定</view>
			<view class="bg">
				<image class="bg-img" src="../../static/images/gemmologist/bg@2x.png" mode=""></image>
				<view class="jd">
					<view class="box box1">
						<image class="info-img" src="../../static/images/gemmologist/免费鉴定bg@2x.png" mode=""></image>
						<view class="title"><text>免费鉴定</text></view>
						<view class="info">
							<image src="../../static/images/gemmologist/组24@2x.png" mode=""></image>
							<text class="number">123</text>
							<text class="text">待鉴定</text>
						</view>
					</view>
					<view class="box box2">
						<image class="info-img" src="../../static/images/gemmologist/免费鉴定bg@2x.png" mode=""></image>
						<view class="title"><text>专业鉴定</text></view>
						<view class="info">
							<image src="../../static/images/gemmologist/组25@2x.png" mode=""></image>
							<text class="number">123</text>
							<text class="text">待鉴定</text>
						</view>
					</view>
				</view>
				<view class="zy">
					<view class="title">专业鉴定</view>
					<view class="cont">
						<view class="item">
							<navigator url="../identificationList/identificationList">
								<view>待鉴定</view>
								<view>23</view>
							</navigator>
						</view>
						<view class="item">
							<view>已鉴定</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>问题商品</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>待解决工单</view>
							<view>23</view>
						</view>
					</view>
				</view>
				<view class="zy">
					<view class="title">
						专业鉴定
						<text>(保价0-2000元)</text>
					</view>
					<view class="cont">
						<view class="item">
							<view>待鉴定</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>已鉴定</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>问题商品</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>待解决工单</view>
							<view>23</view>
						</view>
					</view>
				</view>
				<view class="zy">
					<view class="title">
						专业鉴定
						<text>(保价2000元以上)</text>
					</view>
					<view class="cont">
						<view class="item">
							<view>待鉴定</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>已鉴定</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>问题商品</view>
							<view>23</view>
						</view>
						<view class="item">
							<view>待解决工单</view>
							<view>23</view>
						</view>
					</view>
				</view>
				<view class="zy">
					<view class="cont">
						<view class="item">
							<navigator url="../Learningmaterials/Learningmaterials"></navigator>
							<image src="../../static/images/gemmologist/组26@2x.png" mode=""></image>
							<view>学习资料</view>
						</view>
						<view class="item">
							<navigator url="../Assessmentmanagement/Assessmentmanagement">
								<image src="../../static/images/gemmologist/组29@2x.png" mode=""></image>
								<view>考核管理</view>
							</navigator>
						</view>
						<view class="item">
							<image src="../../static/images/gemmologist/组28@2x.png" mode=""></image>
							<view>提现管理</view>
						</view>
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
export default {
	methods: {
		goBack() {
			uni.navigateBack({
				delta: 1
			});
		}
	}
};
</script>

<style lang="scss">
.FreeAdmission {
	position: relative;
	.custom-title {
		position: absolute;
		width: 100%;
		top: 66rpx;
		left: 0;
		z-index: 3;
		text-align: center;
		font-size: 34rpx;
		color: #ffffff;
	}
}
.bg {
	position: relative;
	.bg-img {
		width: 750rpx;
		height: 240rpx;
		position: absolute;
		left: 0;
		top: 0;
	}
	.box {
		position: absolute;
		top: 165rpx;
		width: 356rpx;
		height: 220rpx;
		padding-left: 38rpx;
		.info-img {
			width: 356rpx;
			height: 220rpx;
			position: absolute;
			left: 0;
			top: 0;
		}
		&.box1 {
			left: 19rpx;
		}
		&.box2 {
			right: 19rpx;
		}
	}
	.title {
		font-family: PingFang-SC-Bold;
		font-size: 26rpx;
		color: #282828;
		padding-top: 28rpx;
		padding-bottom: 28rpx;
		position: relative;
		z-index: 1;
		text {
			font-size: 20rpx;
			margin-left: 10px;
		}
	}
	.info {
		position: relative;
		z-index: 1;
		display: flex;
		align-items: center;
		image {
			width: 70rpx;
			height: 70rpx;
		}
		.number {
			font-family: PingFang-SC-Regular;
			font-size: 50rpx;
			color: #8b8b8b;
			margin-left: 18rpx;
		}
		.text {
			font-family: PingFang-SC-Medium;
			font-size: 24rpx;
			color: #282828;
			margin-left: 14rpx;
		}
	}
	.zy {
		width: 716rpx;
		height: 220rpx;
		position: absolute;
		top: 382rpx;
		left: 0;
		right: 0;
		margin: 0 auto;
		background-image: url('../../static/images/gemmologist/矩形1@2x.png');
		background-repeat: no-repeat;
		background-size: cover;
		padding-left: 38rpx;
		padding-right: 38rpx;
		&:nth-of-type(3) {
			top: 602rpx;
		}
		&:nth-of-type(4) {
			top: 822rpx;
		}
		&:nth-of-type(5) {
			top: 1042rpx;
			.cont {
				align-items: center;
				justify-content: space-around;
				height: 100%;
				image {
					width: 70rpx;
					height: 70rpx;
					margin-bottom: 10rpx;
				}
			}
		}
		.title {
			color: #282828;
			font-size: 26rpx;
			padding-top: 38rpx;
			padding-bottom: 28rpx;
		}
		.cont {
			display: flex;
			padding-left: 28rpx;
			padding-right: 28rpx;
			.item {
				text-align: center;
				view {
					font-size: 24rpx;
					color: #282828;
					&:nth-of-type(2) {
						font-size: 36rpx;
						color: #5e95f4;
						margin-top: 18rpx;
						font-weight: bold;
					}
				}
				margin-left: 75rpx;
				&:nth-of-type(1) {
					margin-left: 0;
				}
			}
		}
	}
}
</style>
