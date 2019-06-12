<template>
  <div @click="clickHandle">

<view class='shop'>
    <image class='shop-img' src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560352217597&di=69ef6a6bcfad177b9c11aa0d0b1c19c2&imgtype=0&src=http%3A%2F%2Fimg1.cache.netease.com%2Fcatchpic%2FB%2FB8%2FB89BD8E3849335A5BD71A0EA24CBBA45.jpg"></image>
    <view class='shop-info'>
        <text class='shop-title ell'>秦始皇兵马俑博物馆</text>
        <text class='shop-address'>地址:临潼区秦始皇陵以东1.5公里处</text>
       <text class='shop-time'>开放时间：8:00-18:00</text>
        <text class='shop-time'>建议游玩时长:2-3小时</text>
      
    </view>
    <view class='shop-star'>
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:92%;">★★★★★</view>
    </view>
 
</view>
 
<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560352419400&di=a2efc18f26d7af2e82ae356b1133217b&imgtype=0&src=http%3A%2F%2Fm.tuniucdn.com%2Ffb2%2Ft1%2FG1%2FM00%2FCF%2F2F%2FCii9EVc8fRqIdpOEAEkdw81KBaUAAF-lQGIuS8ASR3b696_w700_h0_c0_t0.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">大唐芙蓉园</text>
        <text class="shop-address">地址：曲江新区芙蓉西路99号</text>
        <text class="shop-time">开放时间：9:00-22:00</text>
        <text class='shop-time'>建议游玩时长:2-4小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:88%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560947250&di=2c8a358202173b5222706ddb7fd6a734&imgtype=jpg&er=1&src=http%3A%2F%2F5b0988e595225.cdn.sohucs.com%2Fimages%2F20181121%2F22cdad15344b4dd8b844cf30cb329e29.jpeg"></image>
    <view class="shop-info">
        <text class="shop-title ell">华清宫</text>
        <text class="shop-address">地址：临潼区骊山北华清路38号</text>
        <text class="shop-time">开放时间：7:00-18:00</text>
        <text class='shop-time'>建议游玩时长:2-3小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:88%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560352715140&di=094786971b62e721af821b421f7d6e91&imgtype=0&src=http%3A%2F%2Fyouimg1.c-ctrip.com%2Ftarget%2Ftg%2F840%2F983%2F960%2Fd4f74b2b1e2e432eaa7ea20d4e890db5.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">《长恨歌》演出</text>
        <text class="shop-address">地址：临潼区骊山北华清路38号</text>
        <text class="shop-time">开放时间：20:10-23:30</text>
        <text class='shop-time'>建议游玩时长:70分钟</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:94%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560352942876&di=1c9ec1e24b69c8c11cc6853ab76838ed&imgtype=0&src=http%3A%2F%2Fimg8.zol.com.cn%2Fbbs%2Fupload%2F24405%2F24404045.JPG"></image>
    <view class="shop-info">
        <text class="shop-title ell">大雁塔</text>
        <text class="shop-address">地址：雁塔区雁塔路</text>
        <text class="shop-time">开放时间：8:00-18:30</text>
        <text class='shop-time'>建议游玩时长:1-2小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:88%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560353058125&di=06c28b123c486a76917003fa3fa1cb01&imgtype=0&src=http%3A%2F%2Fn.sinaimg.cn%2Fsinacn13%2F585%2Fw2025h960%2F20180627%2F022e-hencxtv1011643.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">大唐不夜城</text>
        <text class="shop-address">地址：雁塔区环塔南路东段6号大雁塔南</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:1-3小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:92%;">★★★★★</view>
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