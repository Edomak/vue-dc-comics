<template>
  <div id="app">
    <Header />
    <Main />
    <BlueLine />
    <Footer />
    <FooterBottom />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import BlueLine from './components/BlueLine.vue';
import Footer from './components/Footer.vue';
import FooterBottom from './components/FooterBottom.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    BlueLine,
    Footer,
    FooterBottom
  }
}
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }
  .container {
    width: 70%;
    margin: 0 auto;
  }
</style>
