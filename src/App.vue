<template>
  <div id="app">
    <AppHeader />
    <main>
      <h1>Welcome to My Website</h1>
      <p>This is the main content area.</p>
    </main>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./common/Header/AppHeader.vue";

export default {
  name: "App",
  components: {
    AppHeader,
  },
};
</script>

<style>
main {
  padding: 20px;
  text-align: center;
}
</style>
