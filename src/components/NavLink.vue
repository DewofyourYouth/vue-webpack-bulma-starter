<template>
  <a class="navbar-item has-text-grey-light" :href="navLinkURL">{{
    navlinkText
  }}</a>
</template>

<script>
export default {
  name: 'NavLink',
  data: () => ({}),
  methods: {},
  props: ['navLinkURL', 'navLinkText']
};
</script>
