<template>
  <div id="app">
    <AppHeader/>
    <CurrentTime/>
  </div>
</template>

<script>
import CurrentTime from "./components/CurrentTime.vue";
import AppHeader from "./components/AppHeader.vue";

export default {
  name: "app",
  components: {
    CurrentTime,
    AppHeader
  }
};
</script>

<style lang="scss" scoped>
</style>
