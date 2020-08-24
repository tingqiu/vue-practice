<template>
  <div class="wrapper">
    <swiper :options="swiperOptions">
      <swiper-slide><img class="swiper-img" src="@/assets/img1.jpg" alt=""></swiper-slide>
      <swiper-slide><img class="swiper-img" src="@/assets/img2.jpg" alt=""></swiper-slide>
      <swiper-slide><img class="swiper-img" src="@/assets/img3.jpg" alt=""></swiper-slide>
      <swiper-slide><img class="swiper-img" src="@/assets/img1.jpg" alt=""></swiper-slide>
      <swiper-slide><img class="swiper-img" src="@/assets/img2.jpg" alt=""></swiper-slide>
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>

</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOptions: {}
    }
  }
}
</script>

<style lang="stylus">
.wrapper
  overflow hidden
  width 100%
  height 0
  padding-bottom 67%
  .swiper-img
      width 100%
</style>
