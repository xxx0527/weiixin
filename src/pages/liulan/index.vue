<template>
<div>
      <i-panel title="您的访问记录">
      <view class="top-padding">
 
        <view v-for="item in travels" :key='item' class="top-padding">
      <i-card :title="item.name"  :extra="item.food" :thumb="item.pic">
        <view slot="content">{{item.sightseeing}}</view>
        <view slot="content">{{item.timen}}</view>
      </i-card>
        </view>  
    </view>
      </i-panel>
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  data () {
    return {
      travels:[],
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
    
    const db=wx.cloud.database({env:'xxx0527-d45a62'})
    db.collection('travels').get().then(
    res=>{
    console.log(res.data)
      this.travels=res.data
    }
    )
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
</style>