<template lang='pug'>
  header
    .icon
      | Citric
    router-link(to="/")
      | Home
    router-link(to="/about")
      | About

</template>

<script lang='ts'>
  import { Component, Prop, Vue } from 'vue-property-decorator';

  @Component
  export default class Header extends Vue {
  }

</script>

<style lang="sass" scoped>
  header
    margin: 0
    padding: 0 40px 0 40px
    height: 60px
    width: 100%
    background: #87ceeb
    box-sizing: border-box
    display: flex
    .icon
      font-size: 24px
      font-weight: bold
      line-height: 60px
      color: white
</style>