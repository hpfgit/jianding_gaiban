<template>
	<view class="container">
		<view class="lists">
			<view class="item">
				<image class="left-image" src="../../static/images/means/0817bg@2x.png" mode="widthFix"></image>
				<view class="item-right">
					<view class="top">
						<text>Air Jordan</text>
						<view class="time">
							<image src="../../static/images/means/时间(3)@2x.png" mode="widthFix"></image>
							<text>2018-02-04</text>
						</view>
					</view>
					<view class="center">
						<view class="info">666102</view>
						<view class="status true"><text>鉴定为真</text></view>
					</view>
				</view>
			</view>
			<view class="item">
				<image class="left-image" src="../../static/images/means/0817bg@2x.png" mode="widthFix"></image>
				<view class="item-right">
					<view class="top">
						<text>Air Jordan</text>
						<view class="time">
							<image src="../../static/images/means/时间(3)@2x.png" mode="widthFix"></image>
							<text>2018-02-04</text>
						</view>
					</view>
					<view class="center">
						<view class="info">666102</view>
						<view class="status false"><text>鉴定为假</text></view>
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script></script>

<style lang="scss">
.lists {
	padding-top: 24rpx;
	.item {
		display: flex;
		width: 690rpx;
		height: 180rpx;
		border-radius: 20rpx;
		background-color: #ffffff;
		margin: 0 auto 24rpx;
		padding: 24rpx;
	}
	.left-image {
		width: 132rpx;
		height: 132rpx;
		border-radius: 10rpx;
	}
	.item-right {
		margin-left: 24rpx;
		flex: 1;
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
			.time {
				text {
					font-size: 24rpx;
					color: #858585;
				}
			}
		}
		.center {
			margin-top: 44rpx;
			display: flex;
			justify-content: space-between;

			.time {
				width: 26rpx;
				height: 28rpx;
			}
			.info {
				width: 110rpx;
				height: 30rpx;
				line-height: 30rpx;
				text-align: center;
				font-size: 26rpx;
				background-image: url('../../static/images/means/组10@2x.png');
				background-size: cover;
			}
			.status {
				&.true {
					background-image: linear-gradient(135deg, rgba(28, 211, 249, 0.5) 0%, rgba(61, 180, 247, 0.5) 39%, rgba(94, 149, 244, 0.5) 100%),
						linear-gradient(#5e95f4, #5e95f4);
					border: solid 2rpx #50b8f7;
				}
				&.false {
					background-color: #dd3133;
					border: solid 2rpx #dd3133;
				}
				background-blend-mode: normal, normal;
				border-radius: 14rpx 14rpx 14rpx 0rpx;
				padding-left: 10rpx;
				padding-right: 10rpx;
				line-height: 30rpx;
				text {
					font-size: 20rpx;
					font-weight: bold;
					color: #fefefe;
				}
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
