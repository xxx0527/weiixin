<template>
<div @click="clickHandle">
   <i-grid i-class="no-border">
    <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/images/客服.png" />
        </i-grid-icon>
        <i-grid-label>客服</i-grid-label>
    </i-grid-item>
 </i-grid>
  <i-panel title="出行当地服务">
      <i-grid i-class="no-border">
      <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/images/紧急支援.png" />
        </i-grid-icon>
        <i-grid-label>紧急支援</i-grid-label>
    </i-grid-item>
       <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/images/清单.png" />
        </i-grid-icon>
        <i-grid-label>出行清单</i-grid-label>
       </i-grid-item>
        <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/images/微领队.png" />
        </i-grid-icon>
        <i-grid-label>微领队</i-grid-label>
    </i-grid-item>
        <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/images/翻译.png" />
        </i-grid-icon>
        <i-grid-label>翻译</i-grid-label>
    </i-grid-item>
      </i-grid>
  </i-panel>
 
<i-panel title="是否对您起到帮助">
     <i-grid i-class="no-border">
     <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/点赞.png" />
        </i-grid-icon>
        <i-grid-label>是</i-grid-label>
    </i-grid-item>
          <i-grid-item i-class="no-border">
        <i-grid-icon>
            <image src="/static/grid/点赞否.png" />
        </i-grid-icon>
        <i-grid-label>否</i-grid-label>
    </i-grid-item>
     </i-grid>
</i-panel>
</div>
 </template>

<style scoped>
div >>> .split {
text-align:center;
}
</style>









