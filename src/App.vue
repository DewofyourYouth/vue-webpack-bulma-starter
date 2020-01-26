<template>
  <div>
    <Hero title="The Best Title Ever!" subtitle="And a darn good subtitle"></Hero>
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
