<template>
  <div id="app">
    <Header />
    <main></main>
    <footer></footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';


export default {
  name: 'App',
  components: {
    Header: Header
  }
}
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }
</style>
