<template>
  <el-row :gutter="0" class="m-header">
    <el-col :span="5">
      <Geo></Geo>
    </el-col>
    <el-col :span="5">
      <user></user>
    </el-col>
    <el-col :span="14">
      <navbar></navbar>
    </el-col>
  </el-row>
</template>

<script>
import Geo from "./geo";
import User from "./user";
import Navbar from "./nav";
export default {
  data() {
    return {};
  },
  components: {
    Geo,
    User,
    Navbar
  }
};
</script>
<style lang='scss'>
@import "@/assets/css/public/header/index.scss";
</style>