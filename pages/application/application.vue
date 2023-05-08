<template>
	<view class="content">
		<img class="bgImg" src="/static/images/jump_head.png" alt="">
		<img class="jump_head2" src="/static/images/jump_head2.png" alt="">
		<view class="end">
			<view class="leCanal leCanal1">
				<img class="jsign" src="/static/images/jsign0.png" alt="">
				<img @click="click1" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">天津资方（金城银行）</p>
			</view>
			<view class="leCanal leCanal2">
				<img class="jsign" src="/static/images/jsign1.png" alt="">
				<img @click="click2" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">浙江资方（宁波银行）</p>
			</view>
			<view class="leCanal leCanal3">
				<img class="jsign" src="/static/images/jsign2.png" alt="">
				<img @click="click3" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">重庆资方（富民银行）</p>
			</view>
			<view class="leCanal leCanal4">
				<img class="jsign" src="/static/images/jsign3.png" alt="">
				<img @click="click4" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">四川资方（新网银行）</p>
			</view>
			<view class="leCanal leCanal5">
				<img class="jsign" src="/static/images/jsign4.png" alt="">
				<img @click="click5" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">杭州资方（杭州银行）</p>
			</view>
			<view class="leCanal leCanal6">
				<img class="jsign" src="/static/images/jsign5.png" alt="">
				<img @click="click6" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">武汉资方（众邦银行-企业版）</p>
			</view>
			<view class="leCanal leCanal7">
				<img class="jsign" src="/static/images/jsign6.png" alt="">
				<img @click="click7" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">武汉资方（众邦银行-个人版）</p>
			</view>
			<view class="leCanal leCanal8">
				<img class="jsign" src="/static/images/jsign7.png" alt="">
				<img @click="click8" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">江苏资方（苏宁银行）</p>
			</view>
			<view class="leCanal leCanal9">
				<img class="jsign" src="/static/images/jsign8.png" alt="">
				<img @click="click9" class="jump_but" src="/static/images/jump_but.png" alt="">
				<p class="name">吉林资方（亿联银行）</p>
			</view>
		</view>
		<uni-popup ref="popup1" mask-closable="true">
			<img src="/static/images/富民.png" alt="" style="width:50%;margin:0 auto;display: block;">
		</uni-popup>
		<uni-popup ref="popup2" mask-closable="true">
			<img src="/static/images/新网.png" alt="" style="width:50%;margin:0 auto;display: block;">
		</uni-popup>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {
			click1() {
				window.location.href =
					'https://sme.kcbebank.com/marketing/share.html?redirect_uri=https%3A%2F%2Fsme.kcbebank.com%2Fsme%3FinviterUserNo%3DUR170848687507914753%26channelNo%3DWECHAT_H5%26channelCode%3D9921623CSkv5%26inviterChannelCode%3D9921623CSkv5%26timestamp%3DkotN8bG5sMJF2weJmXj%252Fw0OBMOeVScTx2shleEsC6%252BA%253D%26actCode%3DorgActCode%26referenceOpenId%3DoMHYr5jqqbXTLdArs1HXDELjwReg';
			},
			click2() {
				window.location.href =
					'https://aaph.nbcb.com.cn/blcs/#/LoanManagement/HomePage?id=QR1681783029153&VNK=7a7e74e5';
			},
			click3() {
				this.$refs.popup1.open('center')
			},
			click4() {
				this.$refs.popup2.open("center")
			},
			click5() {
				window.location.href =
					'https://imax.hzbank.com.cn/NeobankServer/share/view/CompanyLoanNew.html?Y29kZT1TWkhEMiZwbGF0Zm9ybT0wMA==';
			},
			click6() {
				window.location.href =
					"https://direct.z-bank.com/portal-loan/xzsdent/#/index?ChannelSeq=10044ZSDZYQY&SubChannelSeq=zsdbjdkjqd0013";
			},
			click7() {
				window.location.href =
					"https://direct.z-bank.com/portal-loan/xzsdzy/#/index?ChannelSeq=10035ZYZSD&SubChannelSeq=zsdcjdkjqd0013";
			},
			click8() {
				window.location.href =
				"https://onlineloan.suningbank.com/merchant/#/appOther/MicApplyForCreditH5/1/QD1394";
			},
			click9() {
				window.location.href =
					"https://mloan.dashuf.com/bsmpweb/#/uniteLogin?qrNo=DSX82375eb05c4447729c51ab3f13901250&productId=D014&channelNum=XLSA&belongCompany=401900&bsmpInfoId=CQPI202305070000478&productIds=110,224,216,218,160,150";
			},

		}
	}
</script>

<style>
	.content {
		width: 100%;
		background-color: #ff576b;
	}

	.bgImg {
		width: 100%;
	}

	.jump_head2 {
		position: absolute;
		left: 50%;
		transform: translateX(-50%);
		width: 90%;
		top: 820rpx;
	}

	.end {
		display: flex;
		flex-flow: column;
		align-items: center;
		width: 100%;
		padding-top: 18%;
		background-color: #ff576;
	}

	.leCanal {
		position: relative;
		width: 90%;
		background: url("/static/images/j0.png") no-repeat;
		background-size: contain;
		height: 320rpx;
		margin-bottom: 30rpx;
	}

	.leCanal1 {
		margin-top: 30rpx;
	}

	.leCanal2 {
		position: relative;
		width: 90%;
		background: url("/static/images/j1.png") no-repeat;
		background-size: contain;
		height: 320rpx;

	}

	.leCanal3 {
		position: relative;
		width: 90%;
		background: url("/static/images/j2.png") no-repeat;
		background-size: contain;
		height: 320rpx;
	}

	.leCanal4 {
		position: relative;
		width: 90%;
		background: url("/static/images/j3.png") no-repeat;
		background-size: contain;
		height: 320rpx;
	}

	.leCanal5 {
		position: relative;
		width: 90%;
		background: url("/static/images/j4.png") no-repeat;
		background-size: contain;
		height: 320rpx;
	}

	.leCanal6 {
		position: relative;
		width: 90%;
		background: url("/static/images/j5.png") no-repeat;
		background-size: contain;
		height: 320rpx;
	}

	.leCanal7 {
		position: relative;
		width: 90%;
		background: url("/static/images/j6.png") no-repeat;
		background-size: contain;
		height: 320rpx;
	}

	.leCanal8 {
		position: relative;
		width: 90%;
		background: url("/static/images/j7.png") no-repeat;
		background-size: contain;
		height: 320rpx;
	}

	.leCanal9 {
		position: relative;
		width: 90%;
		background: url("/static/images/j8.png") no-repeat;
		background-size: contain;
		height: 320rpx;
	}


	.jsign {
		position: absolute;
		top: 60rpx;
		left: 50%;
		transform: translateX(-50%);
		width: 92rpx;
		height: 92rpx;
	}

	.jump_but {
		position: absolute;
		top: 160rpx;
		left: 50%;
		transform: translateX(-50%);
		width: 70%;
	}

	.j0 {
		width: 100%;
	}

	.name {
		position: absolute;
		width: 100%;
		text-align: center;
		top: 260rpx;
		left: 50%;
		transform: translateX(-50%);
		color: rgb(204, 204, 204);
		font-weight: 700;
		font-size: 32rpx;
	}
</style>