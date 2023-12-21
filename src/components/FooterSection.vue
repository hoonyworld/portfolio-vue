<script setup>
import { footerText } from "@/constants/index";
</script>

<template>
    <footer id="footer" role="contentinfo">
      <div class="footer__inner">
        <div class="footer__info">
          <div class="left">
            <div class="title">
              <a href="/">contact</a>
            </div>
            <p class="desc">CP. 010-4056-1688</p>
          </div>
          <div class="right">
            <h3>SOCIAL</h3>
            <ul>
              <li v-for="(footer, key) in footerText" :key="key">
                <a :href="footer.link">{{ footer.title }}</a>
                <em>{{ footer.dsec }}</em>
              </li>
            </ul>
          </div>
        </div>
        <div class="footer__right">
          &copy; 고급웹프로그래밍 포트폴리오<br />
          Made By DongHoon Lee
        </div>
      </div>
    </footer>
  </template>

<style lang="scss" scoped>
@import "@/assets/scss/section/_footer.scss";
</style>

