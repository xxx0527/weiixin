<template>
  <div @click="clickHandle">
    <i-notice-bar icon="systemprompt" loop>
    {{notice}}，想约你去淋一场樱花雨！！！
    </i-notice-bar>
    <i-grid i-class="no-border">
       <i-grid-item v-for="item in grids" :key="item" i-class="no-border" >
      <i-grid-label>{{item}}</i-grid-label>
      </i-grid-item>
      </i-grid>
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
      <view class="top-padding">
      <i-card title="三亚" i-class="top-padding" extra="东方夏威夷" thumb="http://img18.3lian.com/d/file/201710/09/2ae95e3f2a5ba11e2ed42559fee7683d.png ">
        <view slot="content">沐浴阳光，体验夏日清爽</view>
        <view slot="footer">三亚出发</view>
      </i-card>
      <view class="top-padding"></view>
      <i-card title="上海" i-class="top-padding" extra="迪士尼乐园，外滩" thumb="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1554284673169&di=6c6df4ec71bf3676495e35eefa604562&imgtype=0&src=http%3A%2F%2Fmmbiz.qpic.cn%2Fmmbiz_jpg%2FnRTFiaGdKzZ1GjIqrv8XcAdeDD9ibCyqH2zLj2BJwPTKI6niasNEVnQ9DFnqMuHEa7T4ZwyibuaAvibfRWPjeP3tyQw%2F640%3Fwx_fmt%3Djpeg">
        <view slot="content">体验繁华都市别一样风光</view>
        <view slot="footer">游玩娱乐</view>
      </i-card>
      <view class="top-padding"></view>
      <i-card title="长沙" i-class="top-padding" extra="吃货天堂" thumb="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1554284767027&di=af75470ec9acdd57594a6cb653520d5b&imgtype=0&src=http%3A%2F%2Fimg1.qunarzz.com%2Ftravel%2Fpoi%2F201303%2F14%2F059a64fe36e1fc6fddb12cfb.jpg_r_1024x683x95_cf83a860.jpg">
        <view slot="content">领略文艺气息，吃吃吃，根本停不下来</view>
        <view slot="footer">纵享吃喝玩乐</view>
      </i-card>
      <view class="top-padding"></view>
      <i-card title="香港" i-class="top-padding" extra="购物天堂" thumb="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1554285004190&di=76cfae0f130840a886e3f61c2334df15&imgtype=0&src=http%3A%2F%2Fwww.yilule.com%2Fattached%2Fimage%2F20130113%2F20130113225100_83328.jpg">
        <view slot="content">回忆那些经典港片</view>
        <view slot="footer">购物</view>
      </i-card>
      <view class="top-padding"></view>
      <i-card title="西安" i-class="top-padding" extra="文化古都" thumb="https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=3704155989,3651912196&fm=26&gp=0.jpg">
        <view slot="content">体验历史文化气息</view>
        <view slot="footer">当地特色美食</view>
      </i-card>
      <view class="top-padding"></view>
    </view>
    </i-panel>
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  data () {
    return {
      notice:"2019年4月3日",
      grids:['美食林','旅游攻略','交通出行','景点门票','民宿酒店','更多']
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
