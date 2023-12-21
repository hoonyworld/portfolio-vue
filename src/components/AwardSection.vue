<script setup>
import award1 from "@/assets/img/award1.png";
import award2 from "@/assets/img/award2.png";
</script>

<template>
  <section id="award">
    <div class="award__inner">
      <h2 class="award__title">Award<em> 나의 수상</em></h2>
      <div class="award__wrap">
        <article class="award__item s1">
          <div class="content-box1">
            <img :src="award1" alt="K-Paas" />
            <h3 class="title">콘테스트(Contest)</h3>
          </div>
          <div class="info">
            <span>award</span>
            <span>production period : two months</span>
            <span>use stack : Java</span>
          </div>
        </article>
        <article class="award__item s2">
          <div class="content-box2">
            <img :src="award2" alt="구름톤" />
            <h3 class="title">해커톤(Hackathon)</h3>
          </div>
          <div class="info">
            <span>award</span>
            <span>production period : one day</span>
            <span>use stack : Java</span>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import "@/assets/scss/section/_award.scss";
</style>
