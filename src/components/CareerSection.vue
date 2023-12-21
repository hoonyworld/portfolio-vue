<script setup>
import woowacourse from "@/assets/img/woowacourse.png";
import codingTest from "@/assets/img/codingTest.png";
import naverIntern from "@/assets/img/naverIntern.png";
import certificate from "@/assets/img/certificate.png";
</script>

<template>
  <section id="career">
    <div class="career__inner">
      <h2 class="career__title">career<em> 나의 경력</em></h2>
      <div class="career__wrap">
        <article class="career__item s1">
          <div class="content-box1">
            <img :src="woowacourse" alt="우아한테크코스" />
            <h3 class="title">우아한테크코스(Woowa Course)</h3>
          </div>
          <div class="info">
            <span>career</span>
            <span>production period : a week</span>
            <span>use stack : Java</span>
          </div>
        </article>
        <article class="career__item s2">
          <div class="content-box2">
            <img :src="codingTest" alt="코딩테스트" />
            <h3 class="title">코딩테스트(Coding Test)</h3>
          </div>
          <div class="info">
            <span>career</span>
            <span>production period : one day</span>
            <span>use stack : Java</span>
          </div>
        </article>
        <article class="career__item s3">
          <div class="content-box3">
            <img :src="naverIntern" alt="네이버인턴" />
            <h3 class="title">네이버 인턴(Naver Intern)</h3>
          </div>
          <div class="info">
            <span>career</span>
            <span>production period : four months</span>
            <span>use stack : Java</span>
          </div>
        </article>
        <article class="career__item s4">
          <div class="content-box4">
            <img :src="certificate" alt="자격증" />
            <h3 class="title">자격증(Certificate)</h3>
          </div>
          <div class="info">
            <span>career</span>
            <span>production period : a week</span>
            <span>use stack : Java</span>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import "@/assets/scss/section/_career.scss";
</style>
