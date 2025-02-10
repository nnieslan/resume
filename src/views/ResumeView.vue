<script setup lang="ts">
import SkillSection from '@/components/SkillSection.vue'
import ExperienceSection from '@/components/ExperienceSection.vue'
import EducationSection from '@/components/EducationSection.vue'
</script>

<template>
  <main>
    <SkillSection />
    <ExperienceSection />
    <EducationSection />
  </main>
</template>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
