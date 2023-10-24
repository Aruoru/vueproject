<template>
  <div class="search-bar">
    <input
      v-model="message"
      placeholder="ID Конференции"
      class="search-bar-input"
    />
    <button id="search-bar-btn">ПЕРЕЙТИ</button>
  </div>
</template>

<script>
export default {
  data: () => {
    return {
      message: '',
    };
  },
};
</script>

<style scoped>
.search-bar {
  width: 100%;
  background: #3585f5;
  display: flex;
  align-items: center;
  padding: 30px 332px 30px 332px;
}
#search-bar-btn {
  border-radius: 20px;
  background: #fff;
  padding: 16px 22px;
  margin-left: 20px;
  text-align: center;
  font-size: 16px;
  border: none;

  color: #3585F5;
  font-weight: 800px;
  font-size: 16px;
  font-family: proxima;
}

.search-bar-input{
  padding: 21px 416px 21px 20px;
  border-radius: 20px;
  border: none;
}
</style>
