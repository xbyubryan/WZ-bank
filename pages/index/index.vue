<template>
	<view class="content">
		<img class="bgImg" src="/static/images/firstnew.png" alt="">
		<img @click="jump" class="first_but" src="/static/images/first_but.png" alt="">
	</view>

</template>


<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {
			jump() {
				uni.navigateTo({
					url: '/pages/application/application'
				})
			}
		}
	}
</script>

<style>
	.content {
		position: relative;
		width: 100%;
		background-color: #ee7269;
	}

	.bgImg {
		width: 100%;
	}

	.first_but {
		position: fixed;
		left: 50%;
		transform: translateX(-50%);
		bottom: 0%;
		/* width: 548rpx; */
		width: 274px;
		/* height: 150rpx; */
	}
</style>