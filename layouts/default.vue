<template>
  <div class="app">
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Footer from '~/components/Footer.vue'
export default {
  components: { Footer },
  data() {
    return {}
  },
}
</script>

<style lang="scss">
@import '~/assets/scss/main.scss';

.app {
  padding: 6rem;
  max-width: 192rem;
  margin: 0 auto;
}
</style>
