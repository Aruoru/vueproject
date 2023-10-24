<template>
  <ul class="lang-switcher">
    <li
      v-for="(lang, index) in languages"
      :key="index"
      class="lang-switcher-item"
      @click="$emit('onLangSwitched', lang)"
    >
      {{ lang }}
    </li>

    <!-- <button @click="$emit('onClickedCallMeButton')">call me</button> -->
  </ul>
</template>

<script>
export default {
  name: 'LangSwitcher',
  props: {
    languages: {
      type: Array,
      default: () => [],
    },
  },
  methods: {
    onClick(value) {
      console.log(value);
      this.$emit('onLangSwitched', value);
    },
  },
};
</script>

<style scoped>
.lang-switcher {
  display: flex;
  text-decoration: none;
  font-size: 16px;
  color: #3585f5;
}
.lang-switcher-item {
  cursor: pointer;
  text-decoration: none;
  margin-left: 34px;
  list-style: none;
}

.lang-switcher-item:hover{
  color: #73AAF8;
  text-decoration: underline;
}
</style>
