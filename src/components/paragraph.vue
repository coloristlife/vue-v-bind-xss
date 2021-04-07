<template>
  <p v-text="text" />
</template>

<script>
export default {
  inheritAttrs: false,
  props: {
    text: String,
  },
};
</script>