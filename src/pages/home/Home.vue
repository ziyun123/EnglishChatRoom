<template lang="html">
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
    <home-icons></home-icons>
    <home-rcommend></home-rcommend>
    <home-weekend></home-weekend>
  </div>
</template>

<script>
import HomeHeader from './components/Header.vue'
import HomeSwiper from './components/Swiper.vue'
import HomeIcons from './components/Icons.vue'
import HomeRcommend from './components/Rcommend.vue'
import HomeWeekend from './components/Weekend.vue'

export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwiper,
    HomeIcons,
    HomeRcommend,
    HomeWeekend
  }
}
</script>
<style scoped>
</style>
