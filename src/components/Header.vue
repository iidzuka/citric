<template lang='pug'>
  header.header
    .icon
      | Citric
    
</template>

<script lang='ts'>
  import { Component, Prop, Vue } from 'vue-property-decorator';

  @Component
  export default class Question extends Vue {
  }

</script>

<style lang="sass" scoped>
  .header
    margin: 0
    padding: 0 40px 0 40px
    height: 60px
    width: 100%
    background: #87ceeb
    box-sizing: border-box
    .icon
      font-size: 24px
      font-weight: bold
      line-height: 60px
      color: white
</style>