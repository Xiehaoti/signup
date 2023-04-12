<template>
      <el-space direction="vertical">
        <el-text class="mx-1" size="large">创建你的账号</el-text>
        <el-text class="mx-1" size="small">创建你的账号</el-text>
        <el-input v-model="input" placeholder="Email" />
        <el-button color="#062036" :dark="isDark">注册</el-button>
        <div class="dividerW">
          <el-text class="mx-1" size="small">已经有账号了? <el-link type="primary">点击登录</el-link></el-text>
          <el-divider>
            or
          </el-divider>
        </div>
        <el-button :icon="Search">Google</el-button>
        <el-button :icon="Search">FaceBook</el-button>
      </el-space>
</template>

<script setup>
import { Search } from '@element-plus/icons-vue'
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.el-space{
  width: 300px;
  height: 300px;
}
p{
  font-size: 10px;
}
.el-button{
  width: 192.5px;
}
body{

}
.el-link{
font-size: 12px;
}
.dividerW{
  width: 192.5px;
}

</style>
