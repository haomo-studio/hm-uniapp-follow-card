> 官网: [https://haomo-tech.com](https://haomo-tech.com)

> 作者: 毫末科技

> 邮箱: hxg@haomo-studio.com

## 预览

![预览图片](http://downloads.haomo-tech.com/uniapp/hm-follow-card.png)

[在线效果预览](http://template.uniapp.haomo-tech.com/pages/haomo/test-component/hm-follow-card)

更多毫末科技的uni-app跨端模板，请见[毫末科技uni-app跨端模板](https://haomo-tech.com/sale.html)

## 技术支持

* [uni-app插件市场](https://ext.dcloud.net.cn/plugin?id=1405)

* [npm包](https://www.npmjs.com/package/hm-uniapp-follow-card)

* [github地址](https://github.com/haomo-studio/hm-uniapp-follow-card)

* [gitee地址](https://gitee.com/haomo/hm-uniapp-follow-card)

毫末科技将长期迭代本组件。需要技术支持，请进钉钉群：

<img width="250" src="http://downloads.haomo-tech.com/%E6%AF%AB%E6%9C%ABuniapp%E7%BB%84%E4%BB%B6%E6%8A%80%E6%9C%AF%E6%94%AF%E6%8C%81.jpg">

## 概述

毫末uni-app新闻卡片组件。支持H5/小程序(微信、支付宝、头条、百度、QQ)/App；组件可自适应各种屏幕大小的手机。

## 使用

请使用HBuilderX导入组件。

在script中引用：

```javascript
import HmFollowCard from '@/components/hm-follow-card/index.vue'
export default {
    components: {HmFollowCard}
}
```

在template中使用：

```html
<template>
  <div class="test-component">
    <hm-follow-card :options="options"></hm-follow-card>
  </div>
</template>
<script>
import hmFollowCard from '@/components/hm-components/hm-follow-card/index.vue'

export default {
  components: {
    hmFollowCard
    },
  data() {
    return {
      options: {
          backgroudImage:'/static/hm-follow-card/images/img_24026_0_0.png',
          followText: '+ 关注',
          name: '关注的人',
          personImage: '/static/hm-follow-card/images/img_24026_0_1.png',
          fanNumbers: '784',
          fanNumbersCompany: '个',
          likeImage: '/static/hm-follow-card/images/img_24026_0_2.png',
          likeNumbers: '189',
          likeNumbersCompany: '个'
        }
    };
  },
  methods: {
  }
};
</script>
<style>
</style>


```

## 属性说明

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| options        | Object  | -      | 卡片属性                                                                   |

options对象各个属性说明如下：

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| backgroudImage        | String  | -      | 背景图片                                                                   |
| followText        | String  | -      | 关注按钮文本                                                                   |
| name        | String  | -      | 被关注者姓名                                                                   |
| personImage        | String  | -      | 粉丝图标                                                                   |
| fanNumbers        | String  | -      | 粉丝数量                                                                   |
| fanNumbersCompany        | String  | -      | 粉丝数量单位                                                                   |
| likeImage        | String  | -      | 爱心图标                                                                   |
| likeNumbers        | String  | -      | 爱心数量                                                                   |
| likeNumbersCompany        | String  | -      | 爱心数量单位                                                                   |


## 事件说明


## 更新日志

### 0.0.1(2020-03-10)

* 完成第一个版本
