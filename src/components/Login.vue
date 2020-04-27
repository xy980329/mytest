<template>
  <div class="login_container">
    <el-form class="login_input" label-width="90px" input-width="710px">
      <el-form-item  label="登录名">
        <el-input  ></el-input>
      </el-form-item>
      <el-form-item class="login_input" label="密  码">
        <el-input  ></el-input>
      </el-form-item>
    </el-form>
  </div>

</template>

<script>
    export default {
        name: "login"
    }
</script>

<style scoped>

  .login_container{
    width: 800px;
    height: 350px;
    background: antiquewhite;
    margin: 500px auto;
    border-radius: 4px;
  }
  .login_input{


  }


</style>
