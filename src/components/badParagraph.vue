<template>
  <div>
    <h1>BadParagraph</h1>
    <p v-text="text" />
  </div>
</template>
<script>
export default {
  inheritAttrs: true,
  props: {
    text: String,
  },
};
</script>