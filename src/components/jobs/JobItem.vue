<template>
  <div class="job-item">
    <div class="job-item-grid">
      <div class="job-item-header">
        <div class="icon">
          <slot name="icon"></slot>
        </div>
        <div class="details">
          <h3>{{ title }}</h3>
          <p>{{ subtitle }}</p>
          <p>{{ date }}</p>
        </div>
      </div>
      <div class="experience">
        <slot name="experience"></slot>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'JobItem',
  props: {
    title: {
      type: String,
      required: true,
    },
    subtitle: {
      type: String,
      required: true,
    },
    date: {
      type: String,
      required: true,
    },
    location: {
      type: String,
      required: false,
    },
  },
}
</script>

<style scoped>
.job-item {
  margin-bottom: 20px;
}

.job-item-grid {
  display: flex;
  flex-direction: row;
  gap: 16px;
}

.job-item-header {
  display: flex;
  align-items: top;
  margin-bottom: 20px;
  margin-top: 20px;
  min-width: 30%;
}

.job-item-header .details {
  display: flex;
  flex-direction: column;
}

.icon {
  margin-right: 16px;
}

.job-item h3 {
  margin: 0;
  font-size: 1.2em;
  font-weight: bold;
}

.job-item p {
  margin: 5px 0 0;
  font-size: 1em;
}

.experience {
  margin-top: 20px;
  align-items: top;
}

@media (max-width: 768px) {
  .job-item-grid {
    flex-direction: column;
  }
}
</style>
