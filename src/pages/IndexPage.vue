<template>
  <q-page class="flex flex-center">
    <q-circular-progress
      :value="20"
      size="45px"
      :thickness="1"
      color="grey-8"
      track-color="orange"
      class="q-ma-md"
    />
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    />
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
