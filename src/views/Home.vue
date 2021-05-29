<template>
  <div class="home">
    <InlineComp />
  </div>
</template>

<script>
// @ is an alias to /src

import InlineComp from "../components/inline/InlineComp.vue";

export default {
  name: "Home",
  components: {
    InlineComp,
  },
};
</script>
