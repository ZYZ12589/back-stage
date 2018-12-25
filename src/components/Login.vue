<template>
  <div class="login">
    <el-form ref="form" :model="form" label-width="80px">
      <el-form-item label="活动名称">
        <el-input v-model="form.name"></el-input>
      </el-form-item>
      <el-form-item>
        <el-button type="primary">立即创建</el-button>
        <el-button>取消</el-button>
      </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      form: {

      }
    }
  }
}
</script>

<style lang="less">
  .login {
    width: 100%;
    height: 100%;
    background: url('~@/assets/login-bg.jpg') no-repeat top center;
    background-size: 100% 120%;
    overflow: hidden;
    .el-form {
      width: 350px;
      margin: 200px auto;
      background-color: rgba(255,255,255,.3);
    }
  }
</style>
