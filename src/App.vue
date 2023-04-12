<template>
    <el-container>
      <el-header height="20px">网站图标</el-header>
      <el-main>
        <HelloWorld />
      </el-main>
      <el-footer height="20px">页脚</el-footer>
  </el-container>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1d1d1d;
  margin-top: 60px;
}
.el-main{
  margin-bottom: 30px;
}
body{
  margin: 0;
  padding: 0;
  background-color: rgb(255, 255, 255);
}
</style>
