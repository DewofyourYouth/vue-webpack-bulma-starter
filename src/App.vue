<template>
  <div>
    <Hero></Hero>
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
export default {
  name: "App",
  data: () => ({
    msg: "Hi Mom!"
  }),
  components: {
    Hero
  },
  methods: {}
};
</script>
