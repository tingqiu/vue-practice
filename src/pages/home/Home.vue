<template>
  <div>
    <home-header></home-header>
    <div class="home">home</div>
    <router-link to="/list">列表页</router-link>
  </div>
</template>

<script>
import HomeHeader from '@/pages/home/components/Header.vue'
export default {
  name: 'Home',
  components: {
    HomeHeader
  }
}

</script>

<style>
  .home {
    font-size: 50px;
  }
</style>
