<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem
    title="Microsoft"
    subtitle="SENIOR SDE LEAD"
    date="Apr 2010 - May 2011"
    location="San Francisco, CA"
  >
    <template #icon>
      <img src="@/assets/logos/microsoft-logo.png" alt="Microsoft, Inc. logo" />
    </template>
    <template #experience>
      <p>
        I bridged the gap between research and engineering on the Bing SF team formerly known as
        <a href="http://en.wikipedia.org/wiki/Powerset_(company)" target="_blank">Powerset</a>.
      </p>
      <ul>
        <li>
          Led a team improving local search relevance specifically targeting 10 major metro areas
        </li>
        <li>Coordinated with other teams, scheduling work and resources</li>
        <li>Defined code quality guidelines for the team & implemented code reviews</li>
        <li>Educated new team members on Bing data-mining tool-set and language</li>
        <li>
          Developed distributed data-mining pipelines for extracting & analyzing data for search
          relevance experiments
        </li>
        <li>Built ranking algorithm identifying n-gram fuzzy-matches & false-positives</li>
        <li>Developed a dynamic service to expose NLP features for experimentation</li>
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
