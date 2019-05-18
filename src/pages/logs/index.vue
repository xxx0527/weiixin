<template>
  <div @click="clickHandle">     
      <i-grid i-class="no-border">
 <view>
<view class='container'> 收藏单</view>
    <swiper class="swiper" vertical="true" interval="2000">
        <swiper-item>
          <image src="/static/images/上海.jpg"> </image>
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
    <i-grid-item i-class="no-border">
       <i-grid-icon> 
            <image src="/static/grid/分享.png" />
       </i-grid-icon>
        <i-grid-label>分享</i-grid-label>
   </i-grid-item>
     <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/收藏.png" />
        </i-grid-icon>
        <i-grid-label>收藏</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/编辑.png" />
        </i-grid-icon>
        <i-grid-label>编辑</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/删除.png" />
        </i-grid-icon>
        <i-grid-label>删除</i-grid-label>
    </i-grid-item>
     <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/更多.png" />
        </i-grid-icon>
        <i-grid-label>更多</i-grid-label>
    </i-grid-item>
      </i-grid>
    

</div>
 </template>

<style scoped>
div >>> .no-border {
   border-width: 0pt;
  font-weight: 600;
  font-size: 40rpx;
  font-family: "宋体";
 
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
  height: 800rpx;
}
.swiper image{
  width: 100%;
  height: 1000rpx;
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
  background-color:green;
}

.container{
   width: 800rpx;
 height: 100rpx;
  text-align: center;
}
</style>
