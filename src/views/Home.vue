<template>
<div>
<img src="../assets/logo.png" alt="">
  <YesNo />
  </div>
</template>

<script>
import YesNo from "../components/YesNoComponent.vue";

export default {
  name: "App",
  components: {
    YesNo,
  },
};
</script>

