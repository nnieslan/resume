<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem
    title="COLDWATER SOFTWARE"
    subtitle="VP ENGINEERING"
    date="May 2011 - Aug 2013"
    location="Denver, CO"
  >
    <template #icon>
      <img src="@/assets/logos/coldwater-logo.jpg" alt="Coldwater Software logo" />
    </template>
    <template #experience>
      <p>
        I started this company with two colleagues with the goal of creating business productivity
        products. We funded this through consulting and built the team up to 17 people at the time I
        left.
      </p>
      <ul>
        <li>
          Led our product engineering team and consultant staff, providing professional mentoring
          and architectural oversight
        </li>
        <li>Drove staffing, interviewing and team growth</li>
        <li>Planned product vision and strategy with other ELT peers</li>
        <li>Built a team culture focused on quality, team collaboration and accountability</li>
        <li>
          Consulted across a variety of clients including Architect-level & Application Life-cycle
          Management consulting
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
</style>
