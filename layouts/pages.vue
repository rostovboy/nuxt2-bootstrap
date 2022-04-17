<template>
  <default-layout>
    <div class="container mx-auto">Page Layout extending Base Layout</div>
    <Nuxt />
  </default-layout>
</template>

<script>
import DefaultLayout from '@/layouts/default.vue';
  export default {
    components: {
      DefaultLayout,
    },
  };
</script>
