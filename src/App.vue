<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import IconLogo from './components/icons/IconLogo.vue'
import IconFB from './components/icons/IconFB.vue'
import IconIG from './components/icons/IconIG.vue'
import IconYT from './components/icons/IconYT.vue'
import IconLine from './components/icons/IconLine.vue'
import Footer from './components/FooterComp.vue'
</script>

<template>
  <div class="border-bottom border-2 border-primary">
    <header class="container py-51 header d-flex fw-bold">
      <ul class="d-flex font-jost fs-5 justify-content-between flex-grow-1 me-lg-5 nav">
        <li class="nav-link-spacing1"><RouterLink to="/" class="d-block">About Me</RouterLink></li>
        <li class="nav-link-spacing1">
          <RouterLink to="/" class="d-block">Last Activity</RouterLink>
        </li>
        <li><RouterLink to="/">Policy</RouterLink></li>
        <li class="nav-icon-spacing icon"><IconLogo></IconLogo></li>
        <li class="nav-link-spacing2"><RouterLink to="/" class="d-block">Donate</RouterLink></li>
        <li><RouterLink to="/" class="d-block">Feedback</RouterLink></li>
      </ul>
      <ul class="row ms-auto">
        <li class="col">
          <a href="#"><IconFB /></a>
        </li>
        <li class="col">
          <a href="#"><IconIG /></a>
        </li>
        <li class="col">
          <a href="#"><IconYT /></a>
        </li>
        <li class="col">
          <a href="#"><IconLine /></a>
        </li>
      </ul>
    </header>
  </div>
  <RouterView />
  <Footer></Footer>
</template>

<style lang="scss">

</style>
