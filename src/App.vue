<template>
  <div id="app">
    <good-paragraph v-bind="message" />
    <bad-paragraph v-bind="message" />
  </div>
</template>

<script>
import GoodParagraph from "./components/goodParagraph.vue";
import BadParagraph from "./components/badParagraph.vue";

export default {
  name: "App",
  components: {
    GoodParagraph,
    BadParagraph,
  },
  data() {
    return {
      message: {
        text: "body",
        onClick: "javascript:alert(1);",
      },
    };
  },
};
</script>