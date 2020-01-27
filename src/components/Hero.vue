<template>
  <section class="hero is-dark is-medium is-bold has-text-centered">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">{{ title }}</h1>
        <h2 class="subtitle">{{ subtitle }}</h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Header',
  data: () => ({}),
  methods: {},
  props: ['title', 'subtitle']
};
</script>
