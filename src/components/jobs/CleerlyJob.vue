<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem title="CLEERLY HEALTH" subtitle="CTO" date="May 2021 - Oct 2023">
    <template #icon>
      <img src="@/assets/logos/cleerly-logo.png" alt="Cleerly Health logo" />
    </template>
    <template #experience>
      <p>
        <a href="https://cleerlyhealth.com" target="_blank">Cleerly</a> is building the AI-driven
        platform to detect risk-factors of the world's greatest killer, Coronary Artery Disease
        (CAD). We aim to deliver a new standard of care for CAD and heart-attack prevention. I led
        the Engineering, Product, Data Science, Security and Information Technology functions as we
        built a secure, scalable platform.
      </p>
      <ul>
        <li>
          Tripled Technology team size in 2 years, building the Product team from the ground up
        </li>
        <li>
          Established the InfoSec function, hiring the team and driving through two consecutive
          successful SOC 2 Type 2 audits
        </li>
        <li>
          Developed a multi-year strategic plan and product roadmap balancing innovation and
          scalability
        </li>
        <li>
          Drove the Cleerly ISCHEMIA product through the SDLC and regulatory pathway to successful
          FDA clearance
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
