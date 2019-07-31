<template>
  <div>
    <asd />
    <!-- <homec /> -->
    <gallery />
    <!-- <slider /> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import homec from "@/components/Homec.vue";
// import slider from "@/components/Slider.vue";
import gallery from "./Gallery.vue";
import asd from "@/components/Asd.vue";

export default {
  // name: 'home',
  components: {
    // homec,
    // slider,
    gallery,
    asd
  }
};
</script>
