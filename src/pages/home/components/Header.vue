<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe611;</span>
    </div>
    <div class="header-input"><span class="iconfont">&#xe620;</span>输入城市/景点/游玩主题</div>
    <div class="header-right">城市<span class="iconfont">&#xe62a;</span></div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
    @import '~@/assets/styles/varibles.styl'
    .header
        display flex
        line-height 2.46rem
        background-color $bgColor
        color #ffffff
        .header-left
            width 1.64rem
            float left
        .header-input
            flex 1
            height 2.2rem
            line-height 2.2rem
            margin-top .12rem
            margin-left .2rem
            background #ffffff
            border-radius .3rem
            color #cccccc
            .iconfont
                padding-right .3rem
        .header-right
            width 3.24rem
            float right
            text-align center
</style>
