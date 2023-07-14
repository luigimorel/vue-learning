<script setup lang="ts">
import AboutSection from '@/components/AboutSection.vue'
import BottomCTA from '@/components/BottomCTA.vue'
import CallToAction from '@/components/CallToAction.vue'
import FeaturesSection from '@/components/FeaturesSection.vue'
import Footer from '@/components/FooterSection.vue'
import HeroSection from '@/components/HeroSection.vue'
import NavBar from '../components/NavBar.vue'
import TeamSection from '../components/TeamSection.vue'
</script>

<template>
  <NavBar />
  <HeroSection />
  <AboutSection />
  <FeaturesSection />
  <CallToAction />
  <TeamSection />
  <BottomCTA />
  <Footer />
</template>
