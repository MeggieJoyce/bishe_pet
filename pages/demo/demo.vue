<template>
	<view >
		<view class="box">
			box
		</view>
		</view>
</template>

<script>
	export default {
		data() {
			return {
				isshow:true
				}
			}
		},
		methods: {
		changeShow:function(){
			
		}
			// changeUsername:function(name){
			// 	this.userinfo.username="小红"+name;
			// }
		}
	}
</script>

<style>
	.box{
		height: 300px;
		width: 350px;
		border: 1upx soild #333333;
		background: #F0AD4E;
		display: flex;
	
	}
/* .box>view{
	border: 1upx solid #F2F2F2;
	background: #F0AD4E;
	color: #FFFFFF;
	height: 250upx;
	width: 350upx;
	line-height: 200upx;
	font-size: 30px;
	font-weight: bold;
	text-align: center;
} */
</style>
