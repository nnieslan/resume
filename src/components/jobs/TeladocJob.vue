<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem
    title="TELADOC HEALTH"
    subtitle="VP ENGINEERING"
    date="Nov 2020 - May 2021"
    location="Denver, CO"
  >
    <template #icon>
      <img src="@/assets/logos/teladoc-logo.png" alt="Teladoc Health logo" />
    </template>
    <template #experience>
      <p>
        <a href="https://teladochealth.com" target="_blank">Teladoc Health</a> is the leader in
        whole person virtual care for all. I led the engineering organization formerly known as
        Livongo, driving the chronic condition and mental health product line delivery.
      </p>
      <ul>
        <li>Oversaw a team of 180+ engineers, spanning multiple product lines</li>
        <li>Drove organizational transformation and agile team empowerment</li>
        <li>Developed organizational and technology roadmap</li>
        <li>
          Rapidly integrated with other Teladoc offerings, enhancing continuum of care and member
          experience
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
