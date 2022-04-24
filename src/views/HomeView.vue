<template>
  <div class="home">
    <Header />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header";

export default {
  name: "HomeView",
  components: {
    Header,
  },
};
</script>
<style scoped lang="less">
.home {
  padding: 0 15px;
  background: rgba(0, 0, 0, 50%);
  color: #fff;
}

.bm-header-container .bm-logo .bm-zh > span#text-blue {
  color: var(--theme-color-light-yellow);
}
</style>
