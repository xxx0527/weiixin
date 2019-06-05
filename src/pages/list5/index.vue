<template>
  <div @click="clickHandle">

    <i-notice-bar icon="systemprompt" loop>
    欢迎进入小熊旅游网站，{{notice}}，这个夏天带你遨游世界！！！
    </i-notice-bar>
    <view>
      <swiper class="swiper" autoplay="true" interval="2000">
        <swiper-item>
          <image src="/static/images/上海.jpg"></image>
        </swiper-item>
        <swiper-item>
          <image src="/static/images/乌镇.jpg"></image>
          </swiper-item>
          <swiper-item>
            <image src="/static/images/普罗旺斯.jpg"></image>
          </swiper-item>
           <swiper-item>
            <image src="/static/images/西岛.jpg"></image>
          </swiper-item>
          <swiper-item>
            <image src="/static/images/西藏.jpg"></image>
          </swiper-item>
          <swiper-item>
            <image src="/static/images/重庆.jpg"></image>
          </swiper-item>
         <swiper-item>
            <image src="/static/images/凤凰古城.jpg"></image>
          </swiper-item>
     </swiper>
   </view>

    <i-grid i-class="no-border">
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/1.png" />
        </i-grid-icon>
        <i-grid-label>美食林</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/2.png" />
        </i-grid-icon>
        <i-grid-label>旅游攻略</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/3.png" />
        </i-grid-icon>
        <i-grid-label>交通出行</i-grid-label>
    </i-grid-item>
    </i-grid>
    <i-grid i-class="no-border">
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/4.png" />
        </i-grid-icon>
        <i-grid-label>景点门票</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/5.png" />
        </i-grid-icon>
        <i-grid-label>民宿酒店</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/6.png" />
        </i-grid-icon>
        <i-grid-label>更多</i-grid-label>
    </i-grid-item>
</i-grid>
  <i-panel title="猜你喜欢">
   
<view class="card">
  <text class="card-title">三亚</text>
	<image class='card-img' src='https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559564662248&di=03a27b19f1575472dcf2e6146cd0db09&imgtype=0&src=http%3A%2F%2Fimg.pconline.com.cn%2Fimages%2Fupload%2Fupc%2Ftx%2Fphotoblog%2F1303%2F15%2Fc11%2F18947634_18947634_1363361408421.jpg'></image>
	<text class="card-desc">情侣出游地</text>
  <i-cell title="查看详情" is-link url="/pages/kefu/main"> </i-cell>
</view>
 
<view class="card">
	<text class="card-title">上海</text>
	<image class='card-img' src='https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559564957729&di=06fb1c9e25b43bbaabc869296ed50912&imgtype=0&src=http%3A%2F%2Fs1.sinaimg.cn%2Fmw690%2F002ySfIBzy754HXJQ1Wb0%26690'></image>
	<text class="card-desc">家人一同出行</text>
	<i-cell title="查看详情" is-link url="/pages/kefu/main"> </i-cell>
 </view>
<view class="card">
	<text class="card-title">长沙</text>
	<image class='card-img' src='https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559565277762&di=f182350620da56eb25aae2bb2111cbcc&imgtype=0&src=http%3A%2F%2Fwww.zhongt.com.cn%2Fupload%2FPd15650fc963d4946ac0b9579434a4e05.jpg'></image>
	<text class="card-desc">吃货必打卡地</text>
	<i-cell title="查看详情" is-link url="/pages/kefu/main"> </i-cell>
 </view>
<view class="card">
	<text class="card-title">香港</text>
	<image class='card-img' src='https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559565343760&di=2116661c0d155c5d971e3a45fc640910&imgtype=0&src=http%3A%2F%2Fm.tuniucdn.com%2Ffilebroker%2Fcdn%2Fsnc%2Fbb%2F55%2Fbb55637c1da6aa50c9dccbd183f056d1_w800_h0_c0_t0.jpg'></image>
	<text class="card-desc">购物天堂</text>
	<i-cell title="查看详情" is-link url="/pages/kefu/main"> </i-cell>
 </view>
<view class="card">
	<text class="card-title">西安</text>
	<image class='card-img' src='https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1559565383841&di=2f6278f1290b8a0a90833552f853c8a0&imgtype=0&src=http%3A%2F%2Fimg.pconline.com.cn%2Fimages%2Fupload%2Fupc%2Ftx%2Fitbbs%2F1309%2F23%2Fc49%2F26198385_1379931537586.jpg'></image>
	<text class="card-desc">体验古城别一般风韵</text>
 <i-cell title="查看详情" is-link url="/pages/kefu/main"> </i-cell>
</view>

<!-- <view class='shop'>
    <image class='shop-img' src='http://p1.meituan.net/200.0/dpdeal/5f37afe9ef2dc9c68db49dbe9bfb6c15419781.jpg'></image>
    <view class='shop-info'>
        <text class='shop-title ell'>三亚</text>
        <text class='shop-tel'>地址：海南省南部</text>
        <text class='shop-address'>情侣出游地</text>
        <text class='shop-time'>建议游玩:六月份</text>
      
    </view>
    <view class='shop-star'>
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:50%;">★★★★★</view>
    </view>
 
</view>
 
<view class="shop">
    <image class="shop-img" src="http://p0.meituan.net/200.0/deal/5511b4e5b25fdd67aea0bbca8656ec581139488.jpg@200_0_800_800a%7C267h_267w_2e_90Q"></image>
    <view class="shop-info">
        <text class="shop-title ell">上海</text>
        <text class="shop-tel">地址：上海市</text>
        <text class="shop-address">适合家人旅游</text>
        <text class="shop-time">建议游玩：三，四月份</text>
    </view>
    <view class="shop-star">
        <view class='star-after'>★★★★★</view>
        <view class='star-before' style="width:90%;">★★★★★</view>
    </view>
</view> -->
 
 <!--  <view >
       <i-card @click="goType(item.type)" i-class="split" v-for="item in recommand" :key="item" :extra="item.name" :thumb="item.img">
          <view slot="content">建议游玩：{{item.time}}</view>
          <view slot="footer">地址：{{item.address}}</view>
      </i-card>
    </view>  -->
    
  </i-panel>

  </div>
</template>

<script>
import card from '@/components/card'
import top from '@/data/top.json'

export default {
  data () {
  
    return {
      notice:"夏日打卡地",
      grids:[
      {type:'三亚',img:'/static/images/三亚.jpg',"url":'../list/main?type=1'},
      {type:'上海',img:'/static/images/上海.jpg',"url":'../list/main?type=2'},
      {type:'长沙',img:'/static/images/长沙.jpg',"url":'../list/main?type=3'},
      {type:'香港',img:'/static/images/香港.jpg',"url":'../list/main?type=4'},
      {type:'西安',img:'/static/images/西安.jpg',"url":'../list/main?type=5'}
      ],
      recommand:top
      }
  
   },
  

  components: {
    card
  },

  methods: {
   goList(url){
       mpvue.navigateTo({ url })
   },
     goType(type){
       let url='../list/main?type='+ type
       mpvue.navigateTo({ url })  
      }
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
</style>
