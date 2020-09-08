<template>
	<view>
		<view class="uni-padding-wrap">
		            <view class="page-section swiper">
		                <view class="page-section-spacing">
		                    <swiper class="swiper" indicator-dots=true autoplay=true interval="3000" duration="500">
		                        <swiper-item>
		                            <view class="swiper-item ">
										<image src="https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=1088612344,334638368&fm=26&gp=0.jpg"></image>
									</view>
		                        </swiper-item>
		                        <swiper-item>
		                            <view class="swiper-item ">
										<image src="https://ss2.bdstatic.com/70cFvnSh_Q1YnxGkpoWK1HF6hhy/it/u=2498847639,2277846195&fm=26&gp=0.jpg"></image>
									</view>
		                        </swiper-item>
		                        <swiper-item>
		                            <view class="swiper-item ">
										<image src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=3015675022,1409579087&fm=26&gp=0.jpg"></image>
									</view>
		                        </swiper-item>
								<swiper-item>
								    <view class="swiper-item ">
										<image src="https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=2349876291,3448312520&fm=26&gp=0.jpg"></image>
									</view>
								</swiper-item>
		                    </swiper>
		                </view>
		            </view>
				</view>
				<view>
				<view class="uni-flex uni-row " style="flex-direction: row;">
				                <view class="flex-item " style="background-color: #333333;color: #CCE6FF;width: 25%;">滚</view>
				                <view class="flex-item " style="background-color: #CCE6FF;color:#333333;width: 25%;">滚</view>
				                <view class="flex-item " style="background-color: #333333;color: #CCE6FF;width: 25%;">来</view>
								<view class="flex-item " style="background-color: #CCE6FF;color: #333333;width: 25%;">了</view>
				</view>
				</view>
				<view>
					<view class="uni-flex uni-column">
						<view class="flex-item flex-item-V ">
							<view class="item">
								
							</view>
						</view>
						<view class="flex-item flex-item-V ">
							<view class="item">
								
							</view>
						</view>
						<view class="flex-item flex-item-V ">
							<view class="item">
								
							</view>
						</view>
					</view>
				</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.swiper{
		width: 100%;
		height: 40vh;
	}
	.swiper-item > image{
		width: 100%;
		height: 40vh;
		object-fit: cover;
		overflow: hidden;
	}
	.flex-item-V{
		width: 100%;
		height: 60vh;
		border:1px solid #007AFF;
	}
	.item{
		width: 90%;
		height: 50vh;
		border: 1px solid #39B54A;
		margin: 5vh auto;
	}

</style>
