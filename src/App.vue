<template>
  <router-view />
</template>

<style lang="less">
:root {
  --theme-color-light-yellow: #fcc10e;
  --theme-color-light-blue: #1e2d51;
  --theme-light-text-color: #fff;
}

html,
body {
  padding: 0;
  margin: 0;
}

a {
  text-decoration: none;
  color: var(--theme-light-text-color);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
