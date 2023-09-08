<script>
import AppHero from "./components/AppHero.vue";
export default {
  data() {
    return {
      title: "La mia prima app con vite",
    };
  },
  components: { AppHero },
};
</script>

<template>
  <AppHero />
  <h1>{{ title }}</h1>
</template>

<style></style>
