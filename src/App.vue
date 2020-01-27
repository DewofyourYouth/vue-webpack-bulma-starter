<template>
  <div>
    <NavBar />
    <Hero title="The Best Title Ever!" subtitle="And a darn good subtitle" />
  </div>
</template>

<script>
import Hero from './components/Hero.vue';
import NavBar from './components/NavBar';
export default {
  name: 'App',
  data: () => ({
    msg: 'Hi Mom!'
  }),
  components: {
    Hero,
    NavBar
  },
  methods: {}
};
</script>
