<template>
<div>
  <Header />
  <Main />
  <Footer />
</div>  
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import "~@fortawesome/fontawesome-free/css/all.min.css";
@import "~bootstrap/dist/css/bootstrap.css";
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500&display=swap');
#app {
  *{
    font-family: 'Noto Sans KR', sans-serif;
    box-sizing: border-box;
    margin: 0 auto;
    padding: 0;
  }
 
}
</style>
