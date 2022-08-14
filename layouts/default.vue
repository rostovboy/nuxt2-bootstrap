<template>
  <div>
    <TheHeader />
    <nuxt v-if="!$slots.default" />
    <slot />
    <TheFooter />
  </div>
</template>

<script>
// Это самый основной шаблон в котором есть только блоки наследуемые в других шаблонах
// https://constantsolutions.dk/2020/02/nested-layouts-in-nuxt-vue-js/
</script>