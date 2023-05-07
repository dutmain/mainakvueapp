<template>
  <div class="about">
    <h1>Do you like this app?</h1>
    <button v-on:click="Yes">Yes</button>
    <button v-on:click="No">No</button>
  </div>
</template>
<script>
export default {
  methods: {
    Yes() {
      alert("Thank you!");
    },
    No() {
      alert("I'm sorry!");
    },
  },
};
</script>
