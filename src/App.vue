<template>
  <div id="app">
    <SiteHeader />
    <ContentGo />
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import ContentGo from "./components/ContentGo.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    ContentGo,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
@import "./style/variable.scss";
</style>
