<template>
  <div class="noCont">
    <img src="../../assets/images/noContainer.svg" alt="">
    <p>暂无数据</p>
  </div>
</template>
<script type="text/ecmascript-6">
export default {
  name: 'noCont',
  data () {
    return {
    }
  }
}
</script>
<style lang="stylus" rel="stylesheet/stylus" scoped>
.noCont
  padding 15rem 0
  background #ffffff
  text-align center
  img
    width 10rem
    height 10rem
  p
    font-size 1.4rem
    margin-top 1rem
    color #666666
</style>