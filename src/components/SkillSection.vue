<script setup lang="ts">
import ToolingIcon from './icons/IconTooling.vue'
import LeadershipSkill from './skills/LeadershipSkill.vue'
import MentoringSkill from './skills/MentoringSkill.vue'
import TeamBuildingSkill from './skills/TeamBuildingSkill.vue'
import ArchitectureSkill from './skills/ArchitectureSkill.vue'
import StrategySkill from './skills/StrategySkill.vue'
import SecuritySkill from './skills/SecuritySkill.vue'
</script>

<template>
  <div class="section-divider">
    <hr class="divider-line" />
    <i class="fa-solid fa-toolbox divider-icon"></i><span class="divider-icon">SKILLS</span>
    <hr class="divider-line" />
  </div>

  <div class="skills-grid">
    <LeadershipSkill />
    <SecuritySkill />
    <MentoringSkill />
    <ArchitectureSkill />
    <TeamBuildingSkill />
    <StrategySkill />
  </div>
</template>

<style scoped>
.section-divider {
  display: flex;
  align-items: center;
  margin: 24px 0;
}

.divider-line {
  flex-grow: 1;
  border: none;
  border-top: 1px solid #ccc;
}
.divider-icon {
  font-weight: bolder;
  font-size: 2em;
  padding: 0 16px;
}
.skills-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 10px;
}
@media (min-width: 768px) {
  .skills-grid {
    grid-template-columns: 1fr 1fr;
  }
}
</style>
