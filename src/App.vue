<template>
  <Header />

  <main>
    <HeroSection />
    <Section2 />
    <Section3 />
    <Section4 />
    <Section5 />
    <Section6 />
    <Section7 />
    <Section8 />
  </main>

  <Footer />
</template>

<script>
import HeroSection from '@/components/HeroSection.vue';
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Section2 from '@/components/Section2.vue';
import Section3 from '@/components/Section3.vue';
import Section4 from '@/components/Section4.vue';
import Section5 from '@/components/Section5.vue';
import Section6 from '@/components/Section6.vue';
import Section7 from '@/components/Section7.vue';
import Section8 from '@/components/Section8.vue';

export default {
  components: {
    HeroSection,
    Section2,
    Section3,
    Header,
    Footer,
    Section4,
    Section5,
    Section6,
    Section7,
    Section8,
  
  },
};
</script>

<style>
@font-face {
    font-family: 'proxima';
    src: url('@/fonts/proxima.ttf');
}
</style>
