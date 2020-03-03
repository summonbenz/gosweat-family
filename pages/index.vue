<template>
  <div>
    <Header />
    <div class="container">
      testsdadsa
      <Playlist title="Official MV" />
      <Playlist title="Fanmade MV" />
      <Playlist title="TV Show" />
      <Playlist title="Fancam" />
    </div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'
import Header from '~/components/Header.vue'
import Playlist from '~/components/Playlist.vue'
export default {
  components: {
    // Logo,
    Header,
    Playlist
  }
}
</script>

<style lang="scss">
@import 'assets/custom-vars.scss';

@import '~bootstrap/scss/bootstrap.scss';
@import '~bootstrap-vue/src/index.scss';

@import 'assets/theme.scss';
</style>
