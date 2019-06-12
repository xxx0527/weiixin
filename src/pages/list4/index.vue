<template>
  <div @click="clickHandle">

<view class='shop'>
    <image class='shop-img' src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560351064721&di=2a31915a4ed633fa9e0e82731fc809f9&imgtype=0&src=http%3A%2F%2Fyouimg1.c-ctrip.com%2Ftarget%2Ffd%2Ftg%2Fg4%2FM03%2F8A%2F4D%2FCggYHlXpVCSAF58WAAGPnkOVujM177.jpg"></image>
    <view class='shop-info'>
        <text class='shop-title ell'>迪士尼乐园</text>
        <text class='shop-address'>地址:香港迪士尼乐园度假区</text>
       <text class='shop-time'>开放时间：不定</text>
        <text class='shop-time'>建议游玩时长:8-10小时</text>
      
    </view>
    <view class='shop-star'>
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:96%;">★★★★★</view>
    </view>
 
</view>
 
<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560945941&di=38dc82922bbf7c71d7ee045c2d88907e&imgtype=jpg&er=1&src=http%3A%2F%2Fimg.pconline.com.cn%2Fimages%2Fupload%2Fupc%2Ftx%2Fitbbs%2F1310%2F21%2Fc2%2F27757414_1382317071063.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">维多利亚港</text>
        <text class="shop-address">地址：香港九龙半岛与香港岛之间的海湾</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:1-2小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:90%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560351405110&di=6a3f7a0e6d6a80afb0978852e9dff280&imgtype=0&src=http%3A%2F%2Fn4-q.mafengwo.net%2Fs10%2FM00%2F45%2F6A%2FwKgBZ1lXD1qAddA0AALzOSncFuc01.jpeg"></image>
    <view class="shop-info">
        <text class="shop-title ell">中环摩天轮</text>
        <text class="shop-address">地址：中环民光街33号，中环海滨长廊</text>
        <text class="shop-time">开放时间：11:00-23:00</text>
        <text class='shop-time'>建议游玩时长:0.5-1小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:92%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1726199315,4264834266&fm=26&gp=0.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">太平山顶</text>
        <text class="shop-address">地址：香港岛中环花园道33号</text>
        <text class="shop-time">开放时间：7:00-23:59</text>
        <text class='shop-time'>建议游玩时长:3-5小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:90%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560351676243&di=39f5b8cd0ae49c0465f3a4f39fb834dd&imgtype=0&src=http%3A%2F%2Fimg.mp.itc.cn%2Fupload%2F20170809%2F600b006274844a6baac95bd54c4206c9_th.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">尖沙咀</text>
        <text class="shop-address">地址：香港九龙尖沙咀</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:1天</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:92%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560351866672&di=86fd7a3bf88ce2043a66f3d27d7fab99&imgtype=0&src=http%3A%2F%2F5b0988e595225.cdn.sohucs.com%2Fq_70%2Cc_zoom%2Cw_640%2Fimages%2F20180930%2F22fffe9c887a40c1bbe36fde86b0d88d.jpeg"></image>
    <view class="shop-info">
        <text class="shop-title ell">长洲岛</text>
        <text class="shop-address">地址：香港岛西南海域</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:1-2天</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:90%;">★★★★★</view>
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
