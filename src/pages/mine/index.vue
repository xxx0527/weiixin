<template>
  <div>
    <view class="userinfo">
    <view class="userinfo-avatar">
    <open-data type="userAvatarUrl"></open-data>
    </view>
    <open-data type="userNickName"></open-data>
    </view>
    <i-cell-group>

    <i-cell title="在线客服" is-link url="/pages/kefu/main"> </i-cell>
    
    <i-cell title="我的订单" is-link url="/pages/order/main"> </i-cell>
  
    <i-cell title="我的钱包" is-link url="/pages/money/main"></i-cell>
 
</i-cell-group>
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  data () {
    return {
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
    
    bindViewTap () {
      const url = '../logs/main'
      if (mpvuePlatform === 'wx') {
        mpvue.switchTab({ url })
      } else {
        mpvue.navigateTo({ url })
      }
    },
    clickHandle (ev) {
      console.log('clickHandle:', ev)
      // throw {message: 'custom test'}
    }
  },

  created () {
    // let app = getApp()
  }
}
</script>

<style scoped>
.userinfo {
  display: relative;
  width: 600rpx;
  height: 300rpx;
  color:violet;
  display:flex;
  flex-direction: column;
  align-items: center;
}

.userinfo-avatar {
  overflow: hidden;
  display:block;
  width: 180rpx;
  height:160rpx;
  margin: 20rpx;
  margin-top:50rpx;
  border-radius: 50%;
  border:2px solid #fff;
  box-shadow:3px 3px 10px rgba(0,0,0,0.2);
}
</style>

