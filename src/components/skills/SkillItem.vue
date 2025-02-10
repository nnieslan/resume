<template>
  <div class="skill-item">
    <h3><slot name="icon"></slot> {{ title }}</h3>
    <hr class="divider-line" />
    <p>{{ description }}</p>
  </div>
</template>

<script lang="ts">
export default {
  name: 'SkillItem',
  props: {
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
  },
}
</script>

<style scoped>
.skill-item {
  margin-bottom: 20px;
}
.divider-line {
  flex-grow: 1;
  border: none;
  border-top: 4px solid #ccc;
  margin-right: 200px;
}

.skill-item h3 {
  margin: 0;
  font-size: 1.2em;
  font-weight: bold;
}

.skill-item p {
  margin: 5px 0 0;
  font-size: 1em;
}
</style>
