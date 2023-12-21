<script setup>
import SkipSection from "@/components/SkipSection.vue";
import HeaderSection from "@/components/HeaderSection.vue";
import HomeSection from "@/components/HomeSection.vue";
import AboutMeSection from "@/components/AboutMeSection.vue";
import SkillSection from "@/components/SkillSection.vue";
import StudySection from "@/components/StudySection.vue";
import CareerSection from "@/components/CareerSection.vue";
import AwardSection from "@/components/AwardSection.vue";
import PortSection from "@/components/PortSection.vue";
import OthersSection from "@/components/OthersSection.vue";
import FooterSection from "@/components/FooterSection.vue";
</script>

<template>
  <SkipSection />
  <HeaderSection />
  <main id="main" role="main">
    <HomeSection />
    <AboutMeSection />
    <SkillSection />
    <StudySection />
    <CareerSection />
    <AwardSection />
    <PortSection />
    <OthersSection />
  </main>
  <FooterSection />
</template>
