<template lang="pug">
  include /assets/pug/index
  +b.HEADER.header
    .container 
      app-logo
      | HEADER
</template>

<script>
import component from './header'
export default component
</script>

<style lang="sass">
@import "header.sass"
</style>
