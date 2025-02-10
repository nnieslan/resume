<script setup lang="ts">
import HeroBanner from './components/HeroBanner.vue'
import ResumeView from './views/ResumeView.vue'
</script>

<template>
  <div class="app">
    <header>
      <HeroBanner />
    </header>
    <ResumeView />
  </div>
</template>

<style scoped>
@media screen and (min-width: 1024px) {
  :root {
    --section-gap: 2rem;
  }
  .app {
    min-width: 1028px;
    display: block;
  }

  header {
    /* padding: var(--section-gap) 0 0 0; */

    background-color: #f0f0f0;
  }

  .wrapper {
    display: grid;
    grid-template-columns: 1fr auto;
    align-items: center;
    column-gap: var(--section-gap);
  }
}

header {
  line-height: 1.5;
  max-height: 100vh;
  background-color: var(--color-toggle);
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: block;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: block;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
