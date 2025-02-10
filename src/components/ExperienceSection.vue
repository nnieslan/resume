<script setup lang="ts">
import PlumeJob from './jobs/PlumeJob.vue'
import TuringJob from './jobs/TuringJob.vue'
import CleerlyJob from './jobs/CleerlyJob.vue'
import TeladocJob from './jobs/TeladocJob.vue'
import LivongoJob from './jobs/LivongoJob.vue'
import MyStrengthJob from './jobs/myStrengthJob.vue'
import ColdwaterJob from './jobs/ColdwaterJob.vue'
import MicrosoftPowersetJob from './jobs/MicrosoftPowersetJob.vue'
import MicrosoftFRxJob from './jobs/MicrosoftFRxJob.vue'
</script>
<template>
  <div class="section-divider">
    <hr class="divider-line" />
    <i class="fa-solid fa-laptop-house divider-icon"></i
    ><span class="divider-icon">EXPERIENCE</span>
    <hr class="divider-line" />
  </div>
  <div class="jobs-grid">
    <PlumeJob />
    <TuringJob />
    <CleerlyJob />
    <TeladocJob />
    <LivongoJob />
    <MyStrengthJob />
    <ColdwaterJob />
    <MicrosoftPowersetJob />
    <MicrosoftFRxJob />
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
.jobs-grid {
  display: block;
  grid-template-columns: 1fr;
  gap: 16px;
}

.job-item:nth-child(odd) {
  background-color: var(--color-toggle);
}

.job-item:nth-child(even) {
  background-color: var(--color-background);
}

@media (min-width: 768px) {
  .jobs-grid {
    grid-template-columns: 1fr 1fr;
  }
}
</style>
