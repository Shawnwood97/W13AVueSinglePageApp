<template>
  <section>
    <h2>This is a HERO section!</h2>
  </section>
</template>

<script>
// export for use in other files/components
  export default {
    name: "home-hero"
  }
</script>

<style scoped>
section {
  background: gray;
  display: grid;
  place-items: center;
}

</style>