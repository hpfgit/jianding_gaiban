<template>
	<view class="container">
		<view class="Examination">
			<view class="name">Air Jordan</view>
			<view class="mark-text">备注信息备注信息备注信息</view>
			<view class="imgs">
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
				<view class="img-box">
					<view class="img">
						<image src="../../static/images/examination/IMG_8859@2x.png" mode=""></image>
						<view class="mark">外观</view>
					</view>
				</view>
			</view>
			<view class="trueorfalse">
				<view class="box"><image src="../../static/images/examination/真2@2x.png" mode=""></image></view>
				<view class="box"><image src="../../static/images/examination/假2@2x.png" mode=""></image></view>
			</view>
			<view class="btn">
				进度 (1/100)
				<image src="../../static/images/examination/jianding_jiandingshi_kaoshi_next@2x.png" mode=""></image>
			</view>
		</view>
	</view>
</template>

<script></script>

<style lang="scss">
	.Examination {
		.name {
			font-size: 40rpx;
			color: #282828;
			margin-top: 36rpx;
			margin-left: 36rpx;
		}
		.mark-text {
			font-size: 26rpx;
			color: #282828;
			margin-top: 20rpx;
			margin-left: 36rpx;
			margin-bottom: 40rpx;
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
			background-color: #f3f0ef;
			border-radius: 8rpx;
			overflow: hidden;
			margin-bottom: 30rpx;
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
				color: #ffffff;
				font-size: 22rpx;
			}
		}
	}
}
.trueorfalse {
	display: flex;
	justify-content: space-around;
	position: fixed;
	bottom: 250rpx;
	left: 0;
	width: 100%;
	.box {
		image {
			width: 140rpx;
			height: 110rpx;
		}
	}
}
.btn {
	position: fixed;
	bottom: 0;
	left: 0;
	width: 750rpx;
	height: 97rpx;
	line-height: 97rpx;
	text-align: center;
	background-image: linear-gradient(-90deg, #5e95f4 0%, #6990f7 39%, #738af9 100%), linear-gradient(#eef1f4, #eef1f4);
	background-blend-mode: normal, normal;
	font-size: 30rpx;
	color: #eef1f4;

	image {
		width: 28rpx;
		height: 18rpx;
		margin-left: 10rpx;
	}
}
</style>
