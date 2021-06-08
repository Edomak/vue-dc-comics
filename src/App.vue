<template>
  <div id="app">
    <Header />
    <Jumbotron />
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
import FooterBottom from './components/FooterBottom.vue';
import Jumbotron from './components/Jumbotron.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Main,
    BlueLine,
    Footer,
    FooterBottom
  }
}
</script>

<style lang="scss">
  body {
    font-family: 'Montserrat', sans-serif;
  }
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
