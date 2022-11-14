<!-- app vue -->

<script>
import FirstComponent from "./components/FirstComponent.vue";
export default {
  components: { FirstComponent },
  data() {
    return {
      text: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <h1>{{ text }}</h1>
  <first-component />
</template>

<style></style>
