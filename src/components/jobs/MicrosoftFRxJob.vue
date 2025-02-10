<script setup lang="ts">
import JobItem from './JobItem.vue'
</script>
<template>
  <JobItem title="Microsoft" subtitle="SENIOR SDE" date="Mar 2005 - Apr 2010" location="Denver, CO">
    <template #icon>
      <img src="@/assets/logos/microsoft-logo.png" alt="Microsoft, Inc. logo" />
    </template>
    <template #experience>
      <p>
        Performed design, development and testing on many feature areas of several Microsoft
        Business Intelligence products including Microsoft SQL Server 2008 R2 Master Data Services,
        Microsoft Office PerformancePoint Server, Microsoft Forecaster, & Microsoft FRx.
      </p>
      <ul>
        <li>Collaborated with Microsoft Security teams to secure code-bases from OWASP Top-10</li>
        <li>
          Extended the SQL build system for Master Data Services (MDS) & owned integration of MDS
          into the SharePoint
        </li>
        <li>
          Brought better scalability & performance to the application by extending the architecture
          to 3-tiers
        </li>
        <li>
          Built one of the first Visual Studio TFS end-to-end implementations within Microsoft
        </li>
        <li>
          Developed build infrastructure for code signing, setup, globalization, testing, and other
          standards as well as creating branching strategy for multiple products and versions
        </li>
        <li>Worked across disciplines to build a full SDLC for work items</li>
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
