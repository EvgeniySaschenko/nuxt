<template lang="pug">
  include /assets/pug/index
  +b.NUXT-LINK(to="/").logo
    +e.IMG(src="~assets/img/logo.png").img
</template>

<script>
import component from './logo'
export default component
</script>

<style lang="sass">
@import "logo.sass"
</style>
