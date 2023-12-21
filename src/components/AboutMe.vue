<script setup>
import about from "@/assets/img/about.jpg";
import about2 from "@/assets/img/about2.png";
</script>

<template>
    <section id="aboutMe">
      <div class="aboutMe__inner">
        <h2 class="aboutMe__title">About Me <em> 나에 대해서</em></h2>
        <div class="aboutMe__wrap">
          <article class="aboutMe__item s1">
            <div class="content-box1">
              <img :src="about" alt="어바웃미" />
            </div>
          </article>
          <article class="aboutMe__item s2">
            <div class="content-box2">
              <img :src="about2" alt="어바웃미2" />
            </div>
          </article>
        </div>
      </div>
    </section>
</template>

<style lang="scss">
@import "@/assets/scss/section/_aboutMe.scss";
</style>
