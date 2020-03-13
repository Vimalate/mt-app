<template>
  <div class="m-geo">
      <i class="el-icon-location">{{ $store.state.geo.position.city }}</i>
      <nuxt-link to="/changeCity" class="changeCity">切换城市</nuxt-link>
      [北京，上海，深圳]
  </div>
</template>

<script>
// console.log($store.state.geo.position.city )
export default {
  data () {
    return {
    };
  },

}

</script>
<style lang='scss' scoped>
</style>