<template>
  <div>
    <h1>This is a Counter</h1>
    <p>Click to Increment.</p>
    <p>You have Clicked {{ total }} Times.</p>
  </div>
</template>

<script>
export default {
  name: "Counter",
  data() {
    return {
      total: 0,
    };
  },
  methods: {
    increment() {
      this.total++;
    },
  },
};
</script>

<style scoped>
</style>
