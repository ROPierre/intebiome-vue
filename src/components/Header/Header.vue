<template src="./Header.html"></template>

<script>
import Menu from './Menu/Menu.vue';

export default {
  name: 'header-main',
  components: {
    'top-menu': Menu,
  },
  data() {
    return {
      showMenu: false,
    };
  },
};
</script>

<style src="./Header.css"></style>
