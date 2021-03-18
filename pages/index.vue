<template>
  <div>
    <sample-component />
    <nuxt-link to="/about">About</nuxt-link>
  </div>
</template>

<script>
import SampleComponent from "../components/SampleComponent.vue";

export default {
  components: {
    SampleComponent,
  },
};
</script>
