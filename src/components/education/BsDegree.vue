<script setup lang="ts">
import SchoolItem from './SchoolItem.vue'
</script>
<template>
  <SchoolItem
    title="B.S. Electrical & Computer Engineering"
    subtitle="University of Colorado at Boulder"
    date="1998 - 2002"
  >
    <template #icon>
      <img src="@/assets/logos/cu-logo.svg" />
    </template>
  </SchoolItem>
</template>
<style lang="css" scoped>
p {
  margin-bottom: 1rem;
}
img {
  width: 50px;
  height: auto;
}
</style>
