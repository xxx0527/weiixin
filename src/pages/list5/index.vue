<template>
  <div @click="clickHandle">

<view class='shop'>
    <image class='shop-img' src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559715001191&di=9ece07f30c827f48d57824c12aea4e49&imgtype=0&src=http%3A%2F%2Fyouimg1.c-ctrip.com%2Ftarget%2F10080s000000hlyj9745C.jpg"></image>
    <view class='shop-info'>
        <text class='shop-title ell'>海洋水族馆</text>
        <text class='shop-address'>地址:上海市浦东新区陆家嘴环路1388号</text>
       <text class='shop-time'>开放时间：9:00-21:00</text>
        <text class='shop-time'>建议游玩时长:1-3小时</text>
      
    </view>
    <view class='shop-star'>
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:90%;">★★★★★</view>
    </view>
 
</view>
 
<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559715545156&di=192d14e8119e1211f074955e0cb10f97&imgtype=0&src=http%3A%2F%2Fp1.ssl.cdn.btime.com%2Ft0173110cc3f761f76a.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">杜莎夫人蜡像</text>
        <text class="shop-address">地址：黄浦区人民广场新世界商厦10楼</text>
        <text class="shop-time">开放时间：10:00-21:00</text>
        <text class='shop-time'>建议游玩时长:2-3小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:85%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559715801614&di=1911da81738ce2a76d4fc7ad9ca1690b&imgtype=0&src=http%3A%2F%2Fimg.pconline.com.cn%2Fimages%2Fupload%2Fupc%2Ftx%2Fitbbs%2F1504%2F23%2Fc69%2F5847487_1429790469325_mthumb.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">东方明珠</text>
        <text class="shop-address">地址：浦东新区陆家嘴世纪大道1号</text>
        <text class="shop-time">开放时间：8:00-22:00</text>
        <text class='shop-time'>建议游玩时长:2-3小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:92%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559714077174&di=4558e5161c2163a39e878c217877a4a9&imgtype=0&src=http%3A%2F%2Fimg.pconline.com.cn%2Fimages%2Fupload%2Fupc%2Ftx%2Fitbbs%2F1506%2F02%2Fc1%2F7809865_1433177624198.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">亚龙湾</text>
        <text class="shop-address">地址：亚龙湾国家旅游度假区</text>
        <text class="shop-time">开放时间：8:00-17:30</text>
        <text class='shop-time'>建议游玩时长:3-4天</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:92%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559714234502&di=a43c710bccb9882c9ec28e1b6f2b8d0a&imgtype=0&src=http%3A%2F%2Fs8.sinaimg.cn%2Fmw690%2F003pK4uxty6Fv837p9te7%26690"></image>
    <view class="shop-info">
        <text class="shop-title ell">鸟巢度假村</text>
        <text class="shop-address">地址：吉阳区亚龙湾国际旅游度假区</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:1天</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:88%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559714514584&di=603af805a7ff7c4a5beaf1c48c543178&imgtype=0&src=http%3A%2F%2Fdimg06.c-ctrip.com%2Fimages%2F100h0a0000004fkhi406D_R_1024_10000_Q90.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">解放路步行街</text>
        <text class="shop-address">地址：吉阳区</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:1-2小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:70%;">★★★★★</view>
    </view>
</view>


    </div>
</template>

<script>
import card from '@/components/card'
import top from '@/data/top.json'

export default {
  data () {

   },
  

  components: {
    card
  },

  methods: {

    },
  

  created () {
    // let app = getApp()
  
  }
}
</script>

<style scoped>
div >>> .no-border {
   border-width: 0pt; 
}
.top-padding {
  padding-top: 50rpx;
}
.userinfo {
  display: flex;
  flex-direction: column;
  align-items: center;


}
.swiper{
  width: 100%;
  height: 600rpx;
}
.swiper image{
  width: 100%;
  height: 600rpx;
}
.userinfo-avatar {
  width: 128rpx;
  height: 128rpx;
  margin: 20rpx;
  border-radius: 50%;
}

.userinfo-nickname {
  color: #aaa;
}

.usermotto {
  margin-top: 150px;
}

.form-control {
  display: block;
  padding: 0 12px;
  margin-bottom: 5px;
  border: 1px solid #ccc;
}
.all{
  width:7.5rem;
  height:1rem;
  background-color:blue;
}
.all:after{
  display:block;
  content:'';
  clear:both;
}
.left{
  float:left;
  width:3rem;
  height:1rem;
  background-color:red;
}

.right{
  float:left;
  width:4.5rem;
  height:1rem;
  background-color:rgb(178, 192, 178);
}

.card{
  display: flex;
  flex-direction: column;
  background-color: #fff;
  margin: 60rpx 20rpx;
  padding: 20rpx 30rpx;
  border-radius: 15rpx;
  border: 1rpx solid #ddd;
}
.card-title{
  font-size: 20px;
  margin-bottom: 20rpx;
}
.card-date{
  font-size: 14px;
  color: #ccc;
  margin-bottom: 20rpx;
  padding-bottom: 20rpx;
  border-bottom: 1rpx solid #ddd;
}
.card-img{
  height:400rpx;
  width: 100%;
}
.card-desc{
  font-size: 16px;
  color: #333;
  margin-bottom: 20rpx;
   padding-top: 20rpx;
  padding-bottom: 20rpx;
  border-bottom: 1rpx solid #ddd;
}
.card-read{
  font-size: 14px;
  color: #666;
}
 
/* 伪元素：画上去的箭头 */
.arrow{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.arrow::after{
    content: "";
    width: 15rpx;
    height: 15rpx;
    border-top: 3rpx solid #ccc;
    border-right: 3rpx solid #ccc;
    transform: rotate(45deg);
}

.shop{
  display: flex;
  padding: 20rpx; 
  flex-direction: row;
  border-bottom:1rpx solid #ddd; 
  position: relative;
 
}
.shop-info{
  width:400rpx;
  display: flex;
  flex-direction: column;
  font-size: 12px;
  color: #666;
  
 
}
.shop-img{
  width: 160rpx;
  height: 160rpx;
  margin-right: 20rpx;
}
.shop-title{
  font-size: 16px;
  color: #333;
   width: 380rpx;
}
 
 
/*单行超出宽度变省略号 */
.ell{
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
}
 
/* 星星评分 */
.shop-star{
  right: 20rpx;
  top: 20rpx;
  position: absolute;
}
.star-after{
  color: #e2e2e2;
}
.star-before{
  color: #f19e38;
  position: absolute;
  left: 0rpx;
  top: 0rpx; 
  overflow: hidden;
}

</style>