<template>
  <span class="text-h4 font-weight-bold">{{ title }}</span>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    }
  },
  created() {
    console.log("\nTitle.created() ... start");
  }
};
</script>
