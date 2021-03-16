<template>

  <FooterExample1></FooterExample1>
  <FooterExample2></FooterExample2>
  <FooterExample3></FooterExample3>
  <FooterExample4></FooterExample4>
  <FooterExample5></FooterExample5>
  <FooterExample6></FooterExample6>
  <FooterExample7></FooterExample7>
  <FooterExample8></FooterExample8>
<FooterExample9></FooterExample9>
  <FooterExample10></FooterExample10>

</template>

<script lang="ts">
import { defineComponent } from "vue";
import FooterExample1 from "@/components/FooterExample1.vue";
import FooterExample2 from "@/components/FooterExample2.vue";
import FooterExample3 from "@/components/FooterExample3.vue";
import FooterExample4 from "@/components/FooterExample4.vue";
import FooterExample5 from "@/components/FooterExample5.vue";
import FooterExample6 from "@/components/FooterExample6.vue";
import FooterExample7 from "@/components/FooterExample7.vue";
import FooterExample8 from "@/components/FooterExample8.vue";
import FooterExample9 from "@/components/FooterExample9.vue";
import FooterExample10 from "@/components/FooterExample10.vue";

export default defineComponent({
  name: "FooterExamplesOverviewPage",
  components: {
    FooterExample10,
    FooterExample9,
    FooterExample8,
    FooterExample7,
    FooterExample6, FooterExample5, FooterExample4, FooterExample3, FooterExample2, FooterExample1},
  props: {},
  data() {
    return {};
  },
  setup(props) {
    return {};
  }
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
