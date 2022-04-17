<template>
  <div>
    <TheHeader />
    <nuxt v-if="!$slots.default" />
    <slot />
  </div>
</template>