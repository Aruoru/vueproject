<template>
  <div class="hero-section">
    <div class="hero-content">
      <h1 class="hero-title">ОБЛАЧНАЯ ПЛАТФОРМА СИНХРОННОГО ПЕРЕВОДА</h1>
      <div class="hero-description">
        <p>Организуйте перевод мероприятия за 1-2 часа</p>
        <p>Платите только за время использования</p>
        <p>Откажитесь от дорогостоящего оборудования</p>
      </div>

      <button class="hero-btn">ПОПРОБОВАТЬ БЕСПЛАТНО</button>

      <img src="@/assets/HeroArrow.svg" class="hero-arrow" alt="HeroArrow" />
    </div>
    <SearchBar class="hero-searchbar" />
  </div>
</template>

<script>
import SearchBar from './SearchBar.vue';
export default {
  components: { SearchBar },
  name: 'HeroSection',
};
</script>

<style scoped>
.hero-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  /* height: 100vh; */
  background: linear-gradient(
      180deg,
      rgba(55, 68, 89, 0.6) 0%,
      rgba(0, 132, 253, 0.8) 100%
    ),
    url('@/assets/hero-bg.jpg'), lightgray 50% / cover no-repeat;
}

.hero-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 1000px;
  margin: 0 auto;
  color: white;
  margin: auto;
}
.hero-title {
  text-align: center;
  font-family: proxima;
  font-size: 74px;
  margin-top: 90px;
  font-weight: 800;
  padding-bottom: 26px;
  line-height: 112%; /* 82.88px */
}
.hero-description p {
  text-align: center;
  font-family: proxima;
  font-size: 22px;
  font-style: normal;
  margin-bottom: 40px;
  font-weight: 400;
  line-height: 112%; /* 24.64px */
}
.hero-arrow {
  margin: 0 auto;
  margin-bottom: 15px;
}

.hero-btn {
width: 266px;
height: 48px;
border-radius: 20px;
background-color: white;
font-family: proxima;
border: none;
color: #3585F5;
margin-bottom: 110px;


}
</style>
