<script setup>
import { portText } from "@/constants/index";
</script>

<template>
  <section id="port" ref="horizontalRef">
    <div class="port__inner">
      <h2 class="port__title">
        project <em>나의 프로젝트</em>
      </h2>
      <div class="port__wrap">
        <article 
          v-for="(port, key) in portText" 
          :key="key"
          :class="`port__item p${key+1}`"
          :ref="setSectionRef"
        >
          <span class="num">{{ port.num }}</span>
          <a 
            :href="port.code" 
            target="_blank" 
            class="img" 
            rel="noreferrer noopener"
          >
            <img :src="port.img" :alt="port.name" />
          </a>
          <h3 class="title">{{ port.title }}</h3>
          <p class="desc">{{ port.desc }}</p>
          <a 
            :href="port.view" 
            target="_blank" 
            class="site" 
            rel="noreferrer noopener"
          >
            View Site
          </a>
        </article>
      </div>
    </div>
  </section>
</template>

<script>
import gsap from "gsap";
import ScrollTrigger from "gsap/ScrollTrigger";
gsap.registerPlugin(ScrollTrigger);

export default {
    mounted: function () {
        this.scrollAnimation();
    },
    methods: {
        scrollAnimation() {
            const horSection = gsap.utils.toArray(".port__item");

            gsap.to(horSection, {
                xPercent: -120 * (horSection.length - 1),
                ease: "none",
                scrollTrigger: {
                    trigger: "#port",
                    start: "top 56px",
                    end: "+=3000",
                    pin: true,
                    scrub: 1,
                    markers: false,
                    invalidateOnRefresh: true,
                    anticipatePin: 1,
                }
            });
        }
    }
}
</script>

<style scoped>
@import "@/assets/scss/section/_port.scss";
</style>
