<script setup>
import leets from "@/assets/img/leets.png";
import sopt from "@/assets/img/sopt.png";
import infcon from "@/assets/img/infcon.png";
import sdc from "@/assets/img/sdc.png";
</script>

<template>
  <section id="others">
    <div class="others__inner">
      <h2 class="others__title">Others <em> 추가사항</em></h2>
      <div class="others_description">사진을 클릭하면 상세페이지로 넘어갑니다.</div>
      <div class="others_left_wrapper">
        <a href="http://leets.land" target="_blank" rel="noopener noreferrer">
          <img :src="leets" alt="리츠" />
        </a>
        <a href="https://www.sopt.org/" target="_blank" rel="noopener noreferrer">
          <img :src="sopt" alt="솝트" />
        </a>
      </div>
      <div class="others_right_wrapper">
        <a href="https://www.inflearn.com/conf/infcon-2023" target="_blank" rel="noopener noreferrer">
          <img :src="infcon" alt="인프콘" />
        </a>
        <a href="https://www.sdc-korea.com/" target="_blank" rel="noopener noreferrer">
          <img :src="sdc" alt="에스디씨" />
        </a>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import "@/assets/scss/section/_others.scss";
</style>
