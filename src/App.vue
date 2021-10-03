<template>
  <div id="app">
    <router-view />
    <Scroll></Scroll>
  </div>
</template>
<script>
import Scroll from "./views/scroll.vue";
export default {
  components: {
    Scroll,
  }
};
</script>
<style lang="scss">
</style>
