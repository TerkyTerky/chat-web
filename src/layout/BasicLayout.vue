<template>
  <GlobalHeader />
  <RouterView />
  <GlobalFooter />
</template>

<script setup lang="ts">
import GlobalHeader from '@/components/GlobalHeader/index.vue'
import GlobalFooter from '@/components/GlobalFooter/index.vue'
</script>

<style lang="scss" scoped></style>
