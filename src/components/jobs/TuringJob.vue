<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem title="TURING MEDICAL" subtitle="FRACTIONAL CTO / ADVISOR" date="Nov 2023 - Feb 2025">
    <template #icon>
      <img src="@/assets/logos/turing-logo.png" alt="Turing Medical logo" />
    </template>
    <template #experience>
      <p>
        <a href="https://turingmedical.com" target="_blank">Turing</a> is striving to obtain better
        brain images while saving time and reducing costs. I advised the R&D, Engineering, Product,
        and Security teams providing strategic guidance.
      </p>
      <ul>
        <li>
          Assessed the state of the platform, technology, and organization to identify gaps and
          recommended courses of action
        </li>
        <li>
          Built an Information Security maturity roadmap and worked with the team to implement it
        </li>
        <li>Reviewed collateral and advised throughout FDA submissions</li>
        <li>Advised on organizational structure and role needs</li>
      </ul>
    </template>
  </JobItem>
</template>
<style lang="css" scoped>
p {
  margin-bottom: 1rem;
}
ul {
  padding-left: 1rem;
}
img {
  width: 50px;
  height: auto;
}
a {
  font-weight: bold;
}
</style>
