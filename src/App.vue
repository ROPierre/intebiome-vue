<template>
  <div id="app">
    <header-main />
    <banner-hero />
    <main-content />
    <footer-main />
  </div>
</template>

<script>
import Header from './components/Header/Header.vue';
import Hero from './components/Hero/Hero.vue';
import Main from './components/Main/Main.vue';
import Footer from './components/Footer/Footer.vue';

export default {
  name: 'App',
  components: {
    'header-main': Header,
    'banner-hero': Hero,
    'main-content': Main,
    'footer-main': Footer,
  },
};
</script>

<style lang="scss">
</style>
