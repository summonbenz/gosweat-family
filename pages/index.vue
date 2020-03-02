<template>
  <div>
    <Header />
    <div class="container">
      testsdadsa
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'
import Header from '~/components/Header.vue'

export default {
  components: {
    // Logo,
    Header
  }
}
</script>

<style lang="sass">
// Import custom SASS variable overrides, or alternatively
// define your variable overrides here instead
@import 'assets/custom-vars.scss';

// Import Bootstrap and BootstrapVue source SCSS files
@import '~bootstrap/scss/bootstrap.scss';
@import '~bootstrap-vue/src/index.scss';

// General style overrides and custom classes
body
  background: $black;
  color: $white;
  margin: 0
.my-widget
  color: var(--danger);
</style>
