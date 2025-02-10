<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem title="PLUME HEALTH" subtitle="SVP PRODUCT & TECHNOLOGY" date="Oct 2023 - Present">
    <template #icon>
      <img src="@/assets/logos/plume-logo.png" alt="Plume Health logo" />
    </template>
    <template #experience>
      <p>
        <a href="https://getplume.co" target="_blank">Plume</a> is on a mission to transform every
        trans life, providing gender-affirming care from anywhere. I lead the Engineering, Product,
        Data, Security, and Information Technology teams in creating a secure, seamless, and
        authentic transgender user experience on top of a fractured healthcare ecosystem.
      </p>
      <ul>
        <li>
          Created a multi-year product strategy and roadmap to iteratively expand clinical
          offerings, add a community platform, drive retention, and make Plume the authentic online
          home for trans folx
        </li>
        <li>
          Championed the re-design & re-platform of Plume's purchase experience to maximize purchase
          conversions and streamline ease of use
        </li>
        <li>
          Drove the creation of a Fee-for-Service line of business overseeing RCM integration and
          implementation of claim & copay collections lifecycle.
        </li>
        <li>Owned AI strategy for the company, driving up efficiency and driving down COGS</li>
        <li>
          Built the Information Security Program from the ground up to meet HIPAA & industry
          compliance frameworks
        </li>
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
