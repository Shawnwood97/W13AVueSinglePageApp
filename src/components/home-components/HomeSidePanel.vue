<template>
  <aside>
    <div class="item"><h3>Side Panel item 1</h3></div>
    <div class="item"><h3>Side Panel item 2</h3></div>
    <div class="item"><h3>Side Panel item 3</h3></div>
    <div class="item"><h3>Side Panel item 4</h3></div>
  </aside>
</template>

<script>
// export for use in other files/components
  export default {
    name: "home-side-panel"
  }
</script>

<style scoped>

aside {
  display: grid;
  gap: 5px;
}

  .item {
    height: 300px;
    background:navajowhite;
    display: grid;
    place-items: center;
  }
</style>