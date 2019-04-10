<template>
   <div><i-tabs :current="current_scroll" scroll @change="handleChangeScroll">
    <i-tab key="tab1" title="周边"></i-tab>
    <i-tab key="tab2" title="热门"></i-tab>
    <i-tab key="tab3" title="境内"></i-tab>
    <i-tab key="tab4" title="港澳台"></i-tab>
    <i-tab key="tab5" title="日本"></i-tab>
    <i-tab key="tab6" title="东南亚"></i-tab>
    <i-tab key="tab7" title="欧洲"></i-tab>
    <i-tab key="tab8" title="美洲"></i-tab>
    <i-tab key="tab9" title="澳中东非"></i-tab>
</i-tabs>
       <i-panel title="目的地推荐">     
      <view class="top-padding"></view>
      <i-card title="猜你喜欢" extra="网红" thumb="https://i02piccdn.sogoucdn.com/c0637ad62dc546d9">
        <view slot="content">去看一下你还没去过的那些网红地</view>
        <view slot="footer">总有一款适合你的栖息地！！！</view>
         </i-card>
         </i-panel>
      <i-panel title="当季热门"> 
      <view class="top-padding"></view>
      <i-card title="无限风光" i-class="top-padding" extra="等你来撩" thumb="https://www.5442.com/uploads/allimg/171019/1614514449-3.jpg">
        <view slot="content">陪你一起淋一场樱花雨</view>
        <view slot="footer">最美的时光，整装待发！！！</view>
      </i-card>
      </i-panel>
     <i-panel title="特价旅游">
      <view class="top-padding"></view>
      <i-card title="特惠门票" i-class="top-padding" extra="更多低价抢购" thumb="https://www.cr173.com/up/2017-8/201708021758516153105.png">
        <view slot="content">旅游乐趣</view>
        <view slot="footer">花更少的钱，玩更多的地方！！！</view>
      </i-card>
     </i-panel>
      <view class="top-padding"></view>
    
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  data () {
    return {
      current_scroll:'tabl',
      motto: 'Hello miniprograme',
      userInfo: {
        nickName: 'mpvue',
        avatarUrl: 'http://mpvue.com/assets/logo.png'
      }
    }
  },

  components: {
    card
  },

  methods: {
    handleChangeScroll(detail){
      console.log(detail)
      this.current_scroll = detail.mp.detail.key
      }
    },
    handleChange ({ detail }) {
        this.setData({
            current: detail.key
        });
    },
    handleChangeScroll (event) {
        this.current_scroll = event.mp.detail.key
    },
    clickHandle (ev) {
      console.log('clickHandle:', ev)
      // throw {message: 'custom test'}
    
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

.userinfo-avatar {
  width: 128rpx;
  height: 128rpx;
  margin: 20rpx;
  border-radius: 50%;
}

.userinfo-nickname {
  color: red;
}

.usermotto {
  margin-top: 150px;
}

.form-control {
  display: block;
  padding: 0 12px;
  margin-bottom: 5px;
  border: 1px solid red;
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
</style>
  
