<template>
	<div class="goods-container">
		<!--引用子组件-->
		<goods-top-box></goods-top-box>
		<goods-collocation></goods-collocation>
		<goods-accessories></goods-accessories>
		<goods-around></goods-around>
		<recommend></recommend>
		<hot-product></hot-product>
		<goods-content></goods-content>
		<video></video>
	</div>
</template>

<script>
//	调用子组件对象
	import GoodsTopBox from './GoodsTopBox'
	import GoodsCollocation from './GoodsCollocation'
	import GoodsAccessories from './GoodsAccessories'
	import GoodsAround from './GoodsAround'
	import Recommend from './Recommend'
	import HotProduct from './HotProduct'
	import GoodsContent from './GoodsContent'
	import Video from './Video'

	export default {
//		注册子组件
		components: {
			'goods-top-box': GoodsTopBox,
			'goods-collocation': GoodsCollocation,
			'goods-accessories': GoodsAccessories,
			'goods-around': GoodsAround,
			'recommend': Recommend,
			'hot-product': HotProduct,
			'goods-content': GoodsContent,
			'video': Video
		}
	}
</script>

<style>
	.goods-container {
		width: 100%;
		height: auto;
		background: #f5f5f5;
		padding-bottom: 40px;
	}
</style>