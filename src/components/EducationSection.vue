<script setup lang="ts">
import BsDegree from './education/BsDegree.vue'
</script>
<template>
  <div class="section-divider">
    <hr class="divider-line" />
    <i class="fa-solid fa-toolbox divider-icon"></i><span class="divider-icon"> EDUCATION </span>
    <hr class="divider-line" />
  </div>
  <div class="education-grid">
    <BsDegree />
  </div>
</template>

<style scoped>
.section-divider {
  display: flex;
  align-items: center;
  margin: 24px 0;
}

.divider-line {
  flex-grow: 1;
  border: none;
  border-top: 1px solid #ccc;
}

.divider-icon {
  font-weight: bolder;
  font-size: 2em;
  padding: 0 16px;
}
.education-grid {
  display: block;
  grid-template-columns: 1fr;
  gap: 16px;
}

@media (min-width: 768px) {
  .education-grid {
    grid-template-columns: 1fr 1fr;
  }
}
</style>
