<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
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
	@media (min-width: 768px) { 
		html,
		page,
		body {
			max-width: 375px;
			margin: 0 auto;
		} 
		font-size: 32rpx !important;
	}
</style>
