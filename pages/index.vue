<template>
  <el-container>
  <el-header>朋友圈点赞截图生成器</el-header>
  <el-main>
    <el-row >
      <el-col :span="12"><main-page/></el-col>
      <el-col :span="12" ><preview/></el-col>
    </el-row>
  </el-main>
</el-container>
</template>

<script>
import MainPage from '../components/MainPage.vue'
import Preview from '../components/Preview.vue'
export default {
  components: { MainPage, Preview },
}
</script>

<style>
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
</style>
