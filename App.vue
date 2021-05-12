<script>
	export default {
		onLaunch: function() {
			// tabbar中间按钮点击事件
			uni.onTabBarMidButtonTap(function(e){
				uni.showToast({
					title:'点我干嘛',
					duration: 1500,
					icon:'none'
				});
			})
	
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	.uni-tabbar-border {
		box-shadow: 0 -10px 10px 3px #a2a2a27a;
	}
</style>
