<template>
	<view class="content">
		<view>
			<!-- 滑块 -->
			<swiper :autoplay="true" :interval='2000' :circular='true'>
				<swiper-item>
					<view style="background: #FF7F50;height: 100upx;line-height: 100upx;">A</view>
				</swiper-item>
				<swiper-item>
					<view style="background: red;height: 100upx;line-height: 100upx;">B</view>
				</swiper-item>
				<swiper-item>
					<view style="background: green;height: 100upx;line-height: 100upx;">C</view>
				</swiper-item>
			</swiper>
		</view>
		
	</view>
</template>

<script>
	export default {
		data: {
			
			
		},
		mounted() {
			
		},
		methods:{
			
		}
	}
</script>

<style>
	.content {
		margin-top: 50upx;
		text-align: center;
		height: 400upx;
	}

	.title {
		font-size: 36upx;
	}
</style>
