<script setup lang="ts">
import { register } from 'swiper/element/bundle'
import BannerComp from '@/components/BannerComp.vue'
import AboutComp from '@/components/AboutComp.vue'
import LastActivity from '@/components/LastActivity.vue'
import PolicyComp from '@/components/PolicyComp.vue';
import DonateComp from '@/components/DonateComp.vue';
import FeedBackComp from '@/components/FeedBackComp.vue';
// register Swiper custom elements
register()
</script>

<template>
  <main>
    <BannerComp class="mb-490"/>
    <AboutComp class="mb-257"></AboutComp>
    <LastActivity class="mb-150"></LastActivity>
    <PolicyComp class="mb-217"></PolicyComp>
    <DonateComp class="mb-150"></DonateComp>
    <FeedBackComp class="mb-314"></FeedBackComp>
  </main>
  
</template>
<style lang="scss" scoped>

.mb-490 {
  margin-bottom: 490px;
}
.mb-257{
  margin-bottom: 257px;
}
.mb-217{
  margin-bottom: 217px;
}
.mb-150{
  margin-bottom: 150px;
}
.mb-314{
  margin-bottom: 314px;
}
/* Swiper styles */
</style>