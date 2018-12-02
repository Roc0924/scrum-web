<template>
  <div>
    <el-header class="header">
      <el-row>
        <el-col>
          <div class="head-wrap">Element</div>
        </el-col>
        <el-col>
          <el-tabs>test</el-tabs>
        </el-col>
      </el-row>
    </el-header>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      placeHolder: 'this is header'
    }
  }
}
</script>

<style scoped>
  .header{
    /*background-color: #409EFF;*/
    background-color: #52BE80;
    color: #fff;
    line-height: 60px;
  }
</style>
