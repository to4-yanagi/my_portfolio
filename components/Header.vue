<template>
  <article class="header">
    <h1>{{ siteTitle }}</h1>
  </article>
</template>

<script>
import Mixin from '@/static/mixin'
export default {
  mixins: [Mixin]
}
</script>

<style lang="scss">
.header {
  position: sticky;
  height: 60px;
  line-height: 60px;
  background-color: rgba($color-accent-bg, 0.5);
  font-size: $font-title;
  text-align: center;
}
</style>
