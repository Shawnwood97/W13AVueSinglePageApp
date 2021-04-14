<template>
  <main>
    <div class="main_content">
      <home-hero />
      <home-welcome />
    </div>

      <home-side-panel />

  </main>
</template>

<script>
// Importing the components for the home page
import HomeHero from './home-components/HomeHero.vue'
import HomeSidePanel from './home-components/HomeSidePanel.vue'
import HomeWelcome from './home-components/HomeWelcome.vue'
// Exporting the body, including the sub components for use in App.vue
  export default {
  components: { HomeSidePanel, HomeHero, HomeWelcome },
    name: "page-body"
  }
</script>

<style scoped>
  main {
    min-height: 90vh;
    max-width: 100%;
    background: blue;
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 5px;
    padding: 5px
  }

  .main_content {
    display: grid;
    gap: 5px;

  }
</style>