<template>
  <div @click="clickHandle">
      <i-panel title="支付方式">
      <i-grid i-class="no-border">
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/钱包.png" />
        </i-grid-icon>
        <i-grid-label>钱包</i-grid-label>
    </i-grid-item>
     <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/信用卡.png" />
        </i-grid-icon>
        <i-grid-label>信用卡</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/余额宝.png" />
        </i-grid-icon>
        <i-grid-label>余额宝</i-grid-label>
    </i-grid-item>
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/优惠券.png" />
        </i-grid-icon>
        <i-grid-label>优惠券</i-grid-label>
    </i-grid-item>
      </i-grid>
      </i-panel>
      <i-panel title="添加卡包">
          
      </i-panel>
</div>
 </template>