<template>
  <input type="checkbox" v-model="value" @click="toggleCheckBox" />
</template>

<script>
export default {
  props: ["value"],
  methods: {
    toggleCheckBox() {
      console.log("toggle");
      this.$emit("input", !this.value);
    },
  },
};
</script>
