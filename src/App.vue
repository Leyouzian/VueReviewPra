<template>
  <div class="App">
    <div class="Headernav">
      <div class="logo">
        <img src="../assets/logo.png" alt="logo" />
      </div>
      <div class="Header-title">
        <div class="Header-left">
          <div class="Header-left-item">
            <a href="#">首页</a>
          </div>
          <div>
            <a href="#">关于我们</a>
          </div>
          <div>
            <a href="#">联系我们</a>
          </div>
          <div>
            <a href="#">帮助中心</a>
          </div>
          <div>
            <a href="#">加入我们</a>
          </div>
          <div>
            <a href="#">下载APP</a>
          </div>
        </div>
        <div class="Header-right">
          <div>
            <a href="#">登录</a>
            <a href="#">注册</a>
          </div>
        </div>
      </div>
    </div>
    <div class="content">
      <div>
        
      </div>
      <router-view />
    </div>
  </div>
</template>
<script setup></script>
<style scoped lang="scss">
.App {
  width: 100%;
  height: 100%;
  background-color: #afe0e4;
  display: flex;
  flex-direction: column;
}
.Headernav {
  display: flex;
  padding: 3px 200px;
  width: 100%;
  box-sizing: border-box;
  border: 1px solid #ccc;
  height: 100%;
  .Header-title {
    width: 100%;
    display: flex;
    justify-content: space-between;
  }
  .Header-left {
    display: flex;
    div {
      margin: 0 20px;
    }
  }
}
.content {
  padding: 30px 200px;
  flex: 1;
  height: 100%;
  display: flex;
}
</style>
