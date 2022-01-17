<template>
  <div id="app">
    <!-- header -->
    <Header/>
    <!-- main -->

    <!-- footer -->
  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
@import './style/general.scss';
</style>
