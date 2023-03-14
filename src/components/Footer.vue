<template>
  <p>This Task Tracker was created by {{name}} in {{year}}</p>
</template>

<script>
export default {
  name: "Footer",
  props: {
    name: String,
    year: Number
  }
};
</script>


<style scoped>
</style>