<template>
  <head>
    <title>{{ "page title" }}</title> <!-- @@@ -->
  </head>
  <Header page_title="Main page" />
  <main>
    <section class="flex justify-center m-10">
      <VueLogo animationType="animate-ping" />
      <VueLogo animationType="animate-spin" />
      <VueLogo animationType="animate-bounce" />
      <VueLogo animationType="animate-pulse" />
    </section>
  </main>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import VueLogo from "./components/VueLogo.vue";

export default {
  name: "App",
  components: {
    Header,
    VueLogo,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
