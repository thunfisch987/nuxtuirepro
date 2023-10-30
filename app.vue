<template>
  <div>
    <UVerticalNavigation :links="myLinks"/>
    <NuxtPage/>
  </div>
</template>

<script setup lang="ts">
const myLinks = [
  {
    label: 'Link1',
    to: { name: 'index'}
  },
  {
    label: 'Link2',
    to: '/page2'
  },
  {
    label: 'Link3',
    href: 'https://example.com'
  }
]
</script>
