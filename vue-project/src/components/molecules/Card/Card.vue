<script setup>
defineProps({
  imgUrl: {
    type: String,
    required: true
  }
})
</script>

<template>
  <article>
    <img :src="imgUrl" alt="Image" />
  </article>
</template>

<style scoped>
article {
    width: 100%;
    max-width: 100%;
    height: 100%;
    border: 4px solid #fff;
    border-radius: 21px;
    overflow: hidden;
}
img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>
