<template>
  <div class="header">
    <el-header height="50px">
      <!--<el-button icon="el-icon-tickets" @click="handleOpen"/>-->
      <el-dropdown class="el-dropdown">
        <el-button class="el-button">
          <img alt="" class="avatar" src="../images/portrait.png" />
          {{name}}
          <i class="el-icon-arrow-down el-icon--right"></i>
        </el-button>
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item>个人中心</el-dropdown-item>
          <el-dropdown-item>退出</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
    </el-header>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      name: 'first'
    }
  },
  methods: {
    handleOpen () {
      this.open = !this.open
      console.log(this.open)
    }
  }
}
</script>

<style scoped>
  .header{
    height: 100%;
    width: 100%;
    background: #409EFF;
  }
  .el-dropdown {
    float: right;
    margin-right: 20px;
  }
  .el-button {
    padding: 2px 20px 2px 2px;  // 重置button的样式，去除本有的padding
    border-radius: 5px;
    color: #00B5FF;
    font-size: 14px;
  }
  .avatar {
    width: 50px;
    height: 50px;
    margin-right: 6px;
    border-radius: 5px;
    vertical-align: middle
  }
</style>
