<template src="./BlogCard.html"></template>

<script>
export default {
  name: 'blog-card',
  props: {
    filename: {
      typeof: String,
      default: 'blog1.png',
    },
    alt_img: {
      typeof: String,
      default: 'Illustrative image',
    },
    text: String,
  },
};
</script>

<style src="./BlogCard.css"></style>
