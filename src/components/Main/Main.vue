<template src="./Main.html"></template>

<script>
import ProductCard from './ProductCard/ProductCard.vue';
import BlogCard from './BlogCard/BlogCard.vue';

export default {
  name: 'main-content',
  components: {
    'product-card': ProductCard,
    'blog-card': BlogCard,
  },
};
</script>

<style src="./Main.css"></style>
