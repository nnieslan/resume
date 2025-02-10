<template>
  <div class="school-item">
    <div class="school-item-grid">
      <div class="school-item-header">
        <div class="icon">
          <slot name="icon"></slot>
        </div>
        <div class="details">
          <h3>{{ title }}</h3>
          <p>{{ subtitle }}</p>
          <p>{{ date }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'SchoolItem',
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
  },
}
</script>

<style scoped>
.school-item {
  margin-bottom: 20px;
}

.school-item-grid {
  display: flex;
  flex-direction: row;
  gap: 16px;
}

.school-item-header {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  min-width: 30%;
}

.icon {
  margin-right: 16px;
}

.school-item h3 {
  margin: 0;
  font-size: 1.2em;
}

.school-item p {
  margin: 5px 0 0;
  font-size: 1em;
}

.experience {
  margin-top: 20px;
}

@media (max-width: 768px) {
  .school-item-grid {
    flex-direction: column;
  }
}
</style>
