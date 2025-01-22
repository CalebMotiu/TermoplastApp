<script setup>
defineProps({
  imageSrc: {
    type: String,
    required: true,
  },
  route: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <router-link :to="route" class="flex justify-center w-3/4 h-40 sm:h-60 lg:w-3/5 lg:h-80">
    <img :src="imageSrc" alt="" class="object-cover w-full h-full" />
  </router-link>
</template>

<style></style>
