<template>
  <header class="header">
    <div class="header-content container">
      <img class="header-logo" src="@/assets/logo.svg" alt="logo" />

      <div class="header-nav">
        <a :href="element.path" v-for="(element, i) of menu" :key="i">
          {{ element.name }}
        </a>
      </div>

      <LangSwitcher
        :languages="langs"
        @onLangSwitched="onLangSwitched"
        @onClickedCallMeButton="onCallMe"
      />
    </div>
  </header>
</template>

<script>
import LangSwitcher from './LangSwitcher.vue';

export default {
  components: { LangSwitcher },
  name: 'Header',
  data() {
    return {
      langs: ['Ru', 'En'],
      menu: [
        {
          name: 'РЕШЕНИЯ',
          path: '/solutions',
        },
        {
          name: 'ТАРИФЫ',
          path: '/rates',
        },
        {
          name: 'ПРЕИМУЩЕСТВА',
          path: '/advantages',
        },
        {
          name: 'КЛИЕНТЫ',
          path: '/clients',
        },
        {
          name: 'КОНТАКТЫ',
          path: '/contacts',
        },
      ],
    };
  },
  methods: {
    onLangSwitched(value) {
      console.log('Language switched to ', value);
    },
  },
};
</script>

<style scoped>
.container {
  max-width: 1380px;
}
.header {
  width: 100%;
  height: 80px;
  display: flex;
  align-items: center;
  position: fixed;
  z-index: 100;
  background: #fff;
}
.header-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.header-nav {
  display: flex;
  justify-content: space-between;
  gap: 34px;
  font-size: 16px;
  font-family: proxima;
}

.header-nav a {
  text-decoration: none;
  color: #3585F5;
}

.header-nav a:hover{
  color: #73AAF8;
  text-decoration: underline;
}

.header-logo {
  align-items: center;
}



</style>
