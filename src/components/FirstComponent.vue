<!-- app vue -->

<script>
export default {
  name: "FirstComponent",
  data() {
    return {
      text: "Sono il primo componente!",
    };
  },
};
</script>

<template>
  <h2>{{ text }}</h2>
</template>

<style scoped>
h2 {
  color: blue;
}
</style>
