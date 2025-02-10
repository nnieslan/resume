<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem
    title="MYSTRENGTH"
    subtitle="HEAD OF ENGINEERING"
    date="Mar 2015 - Jan 2019"
    location="Denver, CO"
  >
    <template #icon>
      <img src="@/assets/logos/mystrength-logo.png" alt="myStrength logo" />
    </template>
    <template #experience>
      <p>
        <a href="https://mystrength.com" target="_blank">myStrength</a> was a leading B2B behavioral
        health start-up offering content and tools to those who need it. I came onboard to modernize
        the product, build a highly effective team and impact lives.
      </p>
      <ul>
        <li>
          Built an engineering team of 9 people from scratch hiring developers and automation
          testers
        </li>
        <li>Researched and sourced IT, security & training vendors</li>
        <li>
          Built a DevOps infrastructure & security development life-cycle (SDL) from the ground up
          with a focus on agile delivery methodologies, high quality feature delivery and 2-week
          release cycles
        </li>
        <li>
          Drove the incremental replacement of the legacy flagship application with a modern web
          application stack
        </li>
        <li>
          Oversaw development and testing of new product lines, focused on meeting market demand to
          stay ahead of the competition
        </li>
        <li>Managed the development of a multi-platform native mobile app stack</li>
        <li>
          Led implementation of numerous integrations between customers and large strategic
          partnerships
        </li>
        <li>
          Created a culture of incremental improvement and innovation which balanced technical debt,
          technology research and new feature development
        </li>
        <li>Created performance management & employee growth plans for engineering team members</li>
        <li>
          Responsible for product technical strategy, defining quarterly goals and yearly roadmaps
        </li>
        <li>
          Drove company-wide security as the Information Security Manager ensuring we met HIPAA
          compliance & ISO 27001 standards
        </li>
        <li>
          Coordinated with marketing, account services, implementation & sales teams to ensure
          effective product and integration releases and unified communication
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
