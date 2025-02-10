<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem
    title="LIVONGO"
    subtitle="SR DIRECTOR OF ENGINEERING"
    date="Feb 2019 - Nov 2020"
    location="Denver, CO"
  >
    <template #icon>
      <img src="@/assets/logos/livongo-logo.png" alt="livongo, Inc. logo" />
    </template>
    <template #experience>
      <p>
        <a href="https://www2.livongo.com" target="_blank">Livongo</a> empowered people with chronic
        conditions to live healthier and happier lives. I joined Livongo through the acquisition of
        myStrength to add a first-class behavioral health offering to the company portfolio.
      </p>
      <ul>
        <li>
          Drove the implementation of initial go-to-market integration between myStrength and
          Livongo
        </li>
        <li>
          Site lead for the Denver office, working with recruiting and facilities to build a
          first-class tech work environment
        </li>
        <li>
          Rapidly grew the Denver tech team from 9 to 30+ engineers to facilitate new product
          initiatives
        </li>
        <li>
          Led a team of front-line managers to organize and empower teams to deliver a new Livongo
          BH experience
        </li>
        <li>Drove HITRUST certification for the behavioral health product line</li>
        <li>
          Developed annual product strategy roadmap with Product counterparts, effectively
          estimating budget & resource needs
        </li>
        <li>Worked cross-functionally to improve company recruiting methods and tools</li>
        <li>
          Coordinate with peers to align larger development initiatives, drive overall architecture
          and improve the SDLC
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
