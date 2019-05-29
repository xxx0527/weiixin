<template>
  <div>
    <i-panel title="景点推荐">
      <view>
         <view class="top-padding">
 
        <i-card i-class="split" v-for="item in recommand" :key="item" :extra="item.name" :thumb="item.img">
            <view slot="content">{{item.time}}</view>
            <view slot="footer">地址：{{item.address}}</view>
        </i-card>
      </view>
      </view>
    </i-panel> 

  </div>
</template>

<script>


export default {

  data () {
    return {
      recommand: []
    }
  },

  onLoad (option){
    console.log(option.type)
    this.recommand = require('@/data/' + option.type + '.json')
  },

  created () {
  }
}
</script>

<style scoped>
div >>> .split {
  margin-bottom: 10pt;
  border-color: aqua;
 border:width 5rpx;
 border-style:solid;
 box-shadow: 2px 2px 5px  #cfd8db;
 border-width: 0rpx; 
  font-weight: 600;
  font-size: 20rpx;
  font-family:verdana;




}
.imagesize {
  display: flex;
 height: 100%;

}
.imagesize image{
  width: 800rpx;
  height: 800rpx;
}
</style>
