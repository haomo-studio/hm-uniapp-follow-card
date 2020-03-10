<template>
  <div class="hm-follow-card">
    <div class="container">
      <image class="backgroudImage" :src="options.backgroudImage" />
      <div class="cardHeader">
        <div class="followButton">
          <text class="followText">{{ options.followText }}</text>
        </div>
      </div>
      <div class="cardBottom">
        <text class="name">{{ options.name }}</text>
        <image class="personImage" :src="options.personImage" />
        <text class="fanNumbers">{{ options.fanNumbers }}</text>
        <text class="fanNumbersCompany">{{ options.fanNumbersCompany }}</text>
        <image class="likeImage" :src="options.likeImage" />
        <text class="likeNumbers">{{ options.likeNumbers }}</text>
        <text class="likeNumbersCompany">{{ options.likeNumbersCompany }}</text>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HmFollowCard',
  props: {
    dataId: {
      type: String,
      default: 'hm-follow-card'
    },
    options: {
      type: Object,
      default: function() {
        return {
          backgroudImage:
            './images/img_24026_0_0.png',
          followText: '+ 关注',
          name: '关注的人',
          personImage:
            './images/img_24026_0_1.png',
          fanNumbers: '784',
          fanNumbersCompany: '个',
          likeImage:
            './images/img_24026_0_2.png',
          likeNumbers: '189',
          likeNumbersCompany: '个'
        };
      }
    }
  },
  data() {
    return {};
  },
  methods: {}
};
</script>
<style>
@import './index.response.css';
</style>
