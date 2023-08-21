<script setup lang="ts">
useHead({
  title: 'Vitesse',
  meta: [
    { name: 'description', content: 'es6-vue-template' },
    {
      name: 'theme-color',
      content: () => (isDark.value ? '#00aba9' : '#ffffff'),
    },
  ],
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: () => '/logo.png',
    },
  ],
});
</script>

<template>
  <RouterView />
</template>
