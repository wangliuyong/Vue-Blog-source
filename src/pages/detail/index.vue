<template>
  <div class="index-page">
    <span class="p">{{msg}}</span>
  </div>
</template>

<script>
  export default {
    name: 'Detail',
    data () {
      return {
        msg: '详情页'
      }
    }
  }
</script>

<style scoped  lang="scss" >
  @import './index.scss';
</style>
