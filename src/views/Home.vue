<template>
  <div class="home">
    <el-container>
      <el-header>
        <!-- 顶部 -->
        <Header></Header>
      </el-header>
      <el-container>
        <!-- 侧边栏 -->
        <el-aside width="200px">
          <Aside></Aside>
        </el-aside>
        <el-main>
          <Content></Content>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/views/header";
import Aside from "@/views/aside";
import Content from "@/views/content/content";

export default {
  name: "home",
  components: {
    Header,
    Aside,
    Content
  }
};
</script>
