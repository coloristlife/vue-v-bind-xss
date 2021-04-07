<template>
  <div>
    <h1>GoodParagraph</h1>
    <p v-text="text" />
  </div>
</template>
<script>
export default {
  inheritAttrs: false,
  props: {
    text: String,
  },
};
</script>