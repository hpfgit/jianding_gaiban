<script>
export default {
	onLaunch: function() {
		console.log('App Launch');
	},
	onShow: function() {
		console.log('App Show');
	},
	onHide: function() {
		console.log('App Hide');
	}
};
</script>

<style>
.container {
	min-height: 100vh;
	background-color: #eef1f4;
	overflow: hidden;
}
view {
	box-sizing: border-box;
}
view,
text {
	font-family: 'PingFang SC Medium';
	font-size: 28rpx;
	color: #282828;
}
image {
	vertical-align: middle;
}
</style>
