<template>
<header>
  <div><h1>LOGO</h1></div>
  <a href="#">My Link</a>
  <a href="#">Your Link</a>
  <a href="#">Their Link</a>
</header>
</template>

<script>
// export for use in other files/components
  export default {
    name: "page-header"
  }
</script>

<style scoped>
header {
  display: grid;
  grid-auto-flow: column;
  place-items: center;
  background: red;
  min-height: 5vh;
  max-width: 100%;
}

a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

a:hover {
  color: yellow;
}

</style>