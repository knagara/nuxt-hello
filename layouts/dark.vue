<template>
  <div class="dark">
    <header><h1>Header</h1></header>
    <nuxt />
    <footer><p>Footer</p></footer>
  </div>
</template>

<style scoped>
header,
footer {
  width: 100%;
  text-align: center;
}

.dark {
  background-color: #000;
  color: #fff;
}
</style>