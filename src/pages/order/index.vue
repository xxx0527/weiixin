<template>
   <div>
     <view class="userinfo">
    <view class="userinfo-avatar">
    <open-data type="userAvatarUrl"></open-data>
    </view>
    <open-data type="userNickName"></open-data>
    </view>
    <i-panel title="爱生活，爱旅游，携手出发！！！">
      <i-input :value="name" @change="changeName($event)" title="用户姓名:" autofocus placeholder=" " maxlength="20" />
      <i-input :value="sex" @change="changeAddress($event)" title="用户性别:" placeholder=" " maxlength="20" />
      <i-input :value="address" @change="changeReason($event)" title="目的地:" placeholder=" " maxlength="50" />
       <i-input :value="time" @change="changeReason($event)" title="游玩时间" placeholder=" " maxlength="50" />
       <i-input :value="number" @change="changeReason($event)" title="同行人数" placeholder=" " maxlength="50" />
      <i-input :value="data" @change="changeReason($event)" title="出发日期" placeholder=" " maxlength="50" />
    </i-panel>
    <i-button @click="handleClick" type="warning" size="default">提交信息</i-button>
    <view class="tips">一个关于旅游的小程序，对于热爱旅游的你是否又心动起来，准备收拾行李出发啦，加入我们体验不同的风景，认识不同的人！！！</view>
    
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  data () {
    return {
   name:"",
   sex:"",
   address:"",
   time:"",
   number:"",
   data:""
      }
    
  },

  components: {
    card
  },

  methods: {
        changeName (event) {
      this.name = event.mp.detail.detail.value
    },
    changeSex (event) {
      this.sex = event.mp.detail.detail.value
    },
     changeAddress (event) {
      this.address = event.mp.detail.detail.value
    },
    changeTime(event) {
      this.time = event.mp.detail.detail.value
    },
    changeNumber (event) {
      this.number = event.mp.detail.detail.value
    },
    changeData (event) {
      this.data = event.mp.detail.detail.value
    },
    handleClick () {
      if (this.name && this.sex && this.address && this.time && this.number && this.data) {
        wx.showToast({
          title: '尊敬的' + this.name +'，您去往' + this.address + '于' + this.data +'订单提交完毕，期待你有一个美好旅行！！！',
          icon: 'success',
          duration: 2000
        })
        // TODO:将推荐数据提交到云数据库
      } else {
        wx.showToast({
          title: '信息不完整',
          icon: 'none',
          duration: 2000
        })
      }
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
.userinfo {
  position: relative;
  width: 750rpx;
  height: 320rpx;
  color: #666;
  display: flex;
  flex-direction: column;
  align-items: center;
}
 
.userinfo-avatar {
  overflow:hidden;
  display: block;
  width: 160rpx;
  height: 160rpx;
  margin: 20rpx;
  margin-top: 50rpx;
  border-radius: 50%;
  border: 2px solid #fff;
  box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
}

.tips {
  padding: 20pt;
  font-size: 10pt;
  color:#FFC78E;
}
</style>
  
