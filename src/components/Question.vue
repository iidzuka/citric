<template lang='pug'>
  section#question
    h4 Q{{ number }}
    p {{ title }}
    
    
</template>

<script lang='ts'>
  import { Component, Prop, Vue } from 'vue-property-decorator';

  @Component
  export default class Question extends Vue {
    @Prop() private title!: string;
    @Prop() private number!: number;
  }

</script>

<style lang="sass" scoped>
  #question
    margin: 0 40px 0 40px
</style>