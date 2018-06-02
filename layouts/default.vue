<template>
  <div>
     <app-navigation />
    <nuxt/>
     <app-footer />
  </div>
</template>
<script>
import AppNavigation from './../components/layout/AppNavigation.vue';
import AppFooter from './../components/layout/AppFooter.vue';
export default {
  components: {
    AppNavigation,
    AppFooter
  }
};
</script>

<style>
html,
body {
  height: 100%;
  margin: 0;
}


</style>
