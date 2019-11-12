<template>
<div>
<van-button type="primary">主要按钮</van-button>
    <van-swipe :autoplay="3000">
  <van-swipe-item v-for="(image, index) in images" :key="index">
    <img v-lazy="image" />
  </van-swipe-item>
</van-swipe>
</div>
</template>
<script>
export default {
    name: 'Index',
    data(){
        return {
 images: [
        'https://img.yzcdn.cn/vant/apple-1.jpg',
        'https://img.yzcdn.cn/vant/apple-2.jpg'
      ]
        }
    }
}
</script>