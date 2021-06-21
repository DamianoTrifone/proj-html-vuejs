<template>
  <Header />
</template>

<script>
import Header from './components/Header.vue'
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
@import "~@fortawesome/fontawesome-free/css/all.min.css";
@import "~bootstrap/dist/css/bootstrap.css";
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500&display=swap');
#app {
  font-family: 'Noto Sans KR', sans-serif;
}
</style>
