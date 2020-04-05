<template lang="pug">
  .wrapper
    app-header
    nuxt
    app-footer
</template>

<script>
import AppHeader from '@/components/header/header.vue'
import AppFooter from '@/components/footer/footer.vue'

export default {
  components: {
    AppHeader,
    AppFooter
  }
}
</script>

<style lang="sass">
@import "~assets/style/style.sass"
</style>
