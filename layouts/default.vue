<template>
  <div>
    <Nuxt class="app" />
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
}
</style>
