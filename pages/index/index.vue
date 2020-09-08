<template>
	<view class="content" >		
		<navigator  class="nav" url="/pages/show/show" open-type="switchTab" hover-class="other-navigator-hover">
			<button type="default" plain=true>开始熊猫之旅</button>
		</navigator>
		
		
	</view>	
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {
			goto(){
				console.log("wo tiao l ")
				// wx.switchTab({
				//     url:'pages/home/index/index'
				// })
			}

		}
	}
</script>

<style>
	/* .head{
		width: 100%;
		height: 100%;
		background-color:#000000;
	} */
	.content {
		width: 100%;
		height: 100vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		background-size: 100% 100%;
		justify-content: center;
		overflow: hidden;
		background-image: url(../../static/bg.jpg);
	}
	.nav{
		width: 60%;
		position: absolute;
		top:80vh;
	}
</style>
