# Tabbar

## Props

### tabbar-item

| 属性 | 类型 | 默认 | 说明 |
|-----|-----|-----|-----|
| selected | Boolean | false | 是否选中 |
| show-dot | Boolean | false | 是否显示红色提示点 |
| link | String or Object | - | 字符可直接link="/component/cell", Object写法 :link="{name:'cell'}" ｜

## Events
| 名字 | 参数 | 说明                  |
|------|-----|------------------------|
| on-index-change | index | tabbar选中返回index |

## Slots

| 名字 | 说明 |
|-----|-----|
| icon | 图标 |
| label | 文字 |

## Demo

``` html
<template>
<div>
  <tabbar>
    <tabbar-item>
      <img slot="icon" src="https://o84lhz5xo.qnssl.com/master/src/assets/demo/icon_nav_button.png">
      <span slot="label">Wechat</span>
    </tabbar-item>
    <tabbar-item show-dot>
      <img slot="icon" src="https://o84lhz5xo.qnssl.com/master/src/assets/demo/icon_nav_msg.png">
      <span slot="label">Message</span>
    </tabbar-item>
    <tabbar-item selected>
      <img slot="icon" src="https://o84lhz5xo.qnssl.com/master/src/assets/demo/icon_nav_article.png">
      <span slot="label">Explore</span>
    </tabbar-item>
    <tabbar-item>
      <img slot="icon" src="https://o84lhz5xo.qnssl.com/master/src/assets/demo/icon_nav_cell.png">
      <span slot="label">News</span>
    </tabbar-item>
  </tabbar>
</div>
</template>
```
