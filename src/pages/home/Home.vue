<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
    <div>test</div>
    <div class="home">home</div>
    <router-link to="/list">列表页</router-link>
  </div>
</template>

<script>
import HomeHeader from '@/pages/home/components/Header.vue'
import HomeSwiper from '@/pages/home/components/Swiper.vue'
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwiper
  }
}

</script>

<style>
  .home {
    font-size: 50px;
  }
</style>
