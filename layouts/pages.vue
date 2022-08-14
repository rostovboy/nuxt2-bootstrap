<template>
  <default-layout>
    <div class="container">
      <TheCrumbs />
      <main class="mt-4 mb-4">
        <Nuxt />
      </main>
    </div>
  </default-layout>
</template>

<script>
// https://constantsolutions.dk/2020/02/nested-layouts-in-nuxt-vue-js/
import DefaultLayout from '@/layouts/default.vue';
export default {
  components: {
    DefaultLayout,
  },
};
</script>
