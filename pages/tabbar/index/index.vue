<template>
	<view class="index">
		<view class="box">
			<view class="cu-bar tabbar margin-bottom-xl bg-black">
				<view class="action text-orange">
					<view class="cuIcon-homefill"></view> 首页
				</view>
				<view class="action text-gray">
					<view class="cuIcon-similar"></view> 分类
				</view>
				<view class="action text-gray">
					<view class="cuIcon-recharge"></view>
					积分
				</view>
				<view class="action text-gray">
					<view class="cuIcon-cart">
						<view class="cu-tag badge">99</view>
					</view>
					购物车
				</view>
				<view class="action text-gray">
					<view class="cuIcon-my">
						<view class="cu-tag badge"></view>
					</view>
					我的
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				test: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="less">

</style>
