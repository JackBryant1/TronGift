<template>
  <div class="p-4 position-absolute" style="top: 46%;left: 36%;">
    <div class="fs-2 h-100">Send a gift card to your Friend</div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomeView",
});

setTimeout(() => {
  console.log("writing");
}, 1000);
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
