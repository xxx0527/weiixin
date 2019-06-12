<template>
  <div @click="clickHandle">

<view class='shop'>
    <image class='shop-img' src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560349222658&di=13420231a633c0b9f07353f62e001edd&imgtype=0&src=http%3A%2F%2Fdpic.tiankong.com%2Fih%2Fbf%2FQJ9122765098.jpg%3Fx-oss-process%3Dstyle%2Fshow"></image>
    <view class='shop-info'>
        <text class='shop-title ell'>世界之窗</text>
        <text class='shop-address'>地址：开福区三一大道485号</text>
       <text class='shop-time'>开放时间：9:00-21:00</text>
        <text class='shop-time'>建议游玩时长:0.5-1天</text>
      
    </view>
    <view class='shop-star'>
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:85%;">★★★★★</view>
    </view>
 
</view>
 
<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560349549738&di=9ea21b082a6b7150f377ba5034ab61a1&imgtype=0&src=http%3A%2F%2Fimg1.gtimg.com%2Fhn%2Fpics%2Fhv1%2F64%2F104%2F2174%2F141390934.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">橘子洲</text>
        <text class="shop-address">地址：岳麓区橘子洲头2号</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:3-5小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:90%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560349674836&di=f58b2e8e186cda770876fbe6f80d2efa&imgtype=0&src=http%3A%2F%2Fimg.pconline.com.cn%2Fimages%2Fupload%2Fupc%2Ftx%2Fphotoblog%2F1108%2F03%2Fc2%2F8531167_8531167_1312341687296.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">岳麓山</text>
        <text class="shop-address">地址：登高路58号</text>
        <text class="shop-time">开放时间：全天</text>
        <text class='shop-time'>建议游玩时长:0.5-1小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:90%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560350359584&di=dcf99275a3ab7f15901d1fb07a9d6f28&imgtype=0&src=http%3A%2F%2Fwww.hdsj.com%2Fwp-content%2Fuploads%2F2016%2F06%2F20160622001629-12.jpg"></image>
    <view class="shop-info">
        <text class="shop-title ell">海底世界</text>
        <text class="shop-address">地址：开福区三一大道501号</text>
        <text class="shop-time">开放时间：9:00-18:00</text>
        <text class='shop-time'>建议游玩时长:3-4小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:92%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560350625240&di=a526cf250145d78635d6b376033d147b&imgtype=0&src=http%3A%2F%2Fimg.mp.itc.cn%2Fq_mini%2Cc_zoom%2Cw_640%2Fupload%2F20170306%2F378ae887b1984d5ea0a1b1c3bb23eb1c_th.jpeg"></image>
    <view class="shop-info">
        <text class="shop-title ell">湖南省博物馆</text>
        <text class="shop-address">地址：开福区东风路50号</text>
        <text class="shop-time">开放时间：9:00-17:00</text>
        <text class='shop-time'>建议游玩时长:2-5小时</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:80%;">★★★★★</view>
    </view>
</view>

<view class="shop">
    <image class="shop-img" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560947913&di=bcdf12d64d34b0d77aa8a0652c2d7770&imgtype=jpg&er=1&src=http%3A%2F%2Fp1.ssl.cdn.btime.com%2Ft016ffeeea228ffa66d.jpg%3Fsize%3D1600x738"></image>
    <view class="shop-info">
        <text class="shop-title ell">华谊兄弟电影小镇</text>
        <text class="shop-address">地址：岳麓区坪塘街道星光路6号</text>
        <text class="shop-time">开放时间：9:30-21:30</text>
        <text class='shop-time'>建议游玩时长:4-6小时</text>
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
