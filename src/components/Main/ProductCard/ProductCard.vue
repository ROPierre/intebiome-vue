<template src="./ProductCard.html"></template>

<script>
export default {
  name: 'product-card',
  props: {
    filename: {
      typeof: String,
      default: 'product-wellness.png',
    },
    text: String,
    button_color: {
      typeof: String,
      default: '#389CD6',
    },
    button_link: String,
    button_text: String,
  },
};
</script>

<style src="./ProductCard.css" scoped></style>
