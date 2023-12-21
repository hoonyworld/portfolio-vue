<script setup>
import donghoonlee from "@/assets/img/donghoonlee.jpg";
import arrow from "@/assets/img/arrow.png";
</script>

<template>
  <div class="home" id="home">
    <div class="home_left_wrapper">
      <div class="greetings_group">
        <p class="greetings_top">
          안녕하세요
          <br />
          백엔드 개발자
          <br />
          이동훈입니다
        </p>
        <hr class="greetings_under_line" />
        <p class="greetings_bottom">방문해 주셔서 감사합니다</p>
      </div>
    </div>
    <div class="home_right_wrapper">
      <img class="donghoonticon" :src="donghoonlee" alt="" />
    </div>
    <div class="arrow">
      <img class="animateDown" :src="arrow" alt="" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
@import "@/assets/scss/section/_home.scss";
</style>
