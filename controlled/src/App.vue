<template>
  <check-box v-model="checked"></check-box>
</template>

<script>
import CheckBox from "./components/CheckBox.vue";

export default {
  components: {
    CheckBox,
  },
  data() {
    return {
      checked: false,
    };
  },
  methods() {
    fetchCheckBox().then((result) => (this.checked = result.checked));
  },
};
</script>
