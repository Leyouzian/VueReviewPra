<template>
  <div class="App">
    <div class="Headernav">
      <div class="logo">
        <img src="../assets/logo.png" alt="" />
      </div>
      <div class="Header-title">
        <div class="Header-left">
          <div class="Header-left-item">
            <a href="#">BOSS 直聘</a>
          </div>
          <div>
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
    <div class="banner">
      <img
        src="https://img.bosszhipin.com/static/file/2024/mctx1cdg891707037634775.png"
        alt="banner"
      />
    </div>
    <div class="content">
      <div>
        <input type="text" />
      </div>
      <div class="content-Centeritem">
        <div>热门职位：</div>
        <div class="content-Centeritem-right">
          <a href="#">前端工程师</a>
          <a href="#">产品经理</a>
          <a href="#">产品经理</a>
          <a href="#">产品经理</a>
          <a href="#">产品经理</a>
          <a href="#">产品经理</a>
          <a href="#">产品经理</a>
          <a href="#">产品经理</a>
        </div>
      </div>
      <!-- <div class="content-item">
        <div class="content-item-left">
          <div>aaaa</div>
          <div>bbbb</div>
          <div>cccc</div>
          <div>dddd</div>
          <div>eeee</div>
          <div>ffff</div>
          <div>gggg</div>
          <div>hhhh</div>
          <div>iiii</div>
          <div>jjjj</div>
          <div>kkkk</div>
          <div>llll</div>
        </div>
        <div class="content-item-right">
          <router-view />
        </div>
      </div> -->
    </div>
  </div>
</template>
<script setup></script>
<style scoped lang="scss">
.App {
  width: 100%;
  height: 100%;
  background-color: #e2f2f5;
  display: flex;
  flex-direction: column;
}
.Headernav {
  display: flex;
  padding: 15px 160px;
  width: 100%;
  box-sizing: border-box;
  // border: 1px solid #ccc;
  height: 100%;
  background-color: #202329;
  a {
    color: aliceblue;
    // list-style: none;
    text-decoration: none;
  }
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
    .Header-left-item {
      color: #00b4b3;
    }
  }
}
.banner {
  width: 100%;
  height: 120px;
  background-color: #00b4b3;
  padding: 0 160px 0px;
  box-sizing: border-box;
  img {
    height: 120px;
  }
}
.content {
  padding: 30px 200px;
  flex: 1;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  // justify-content: center;
  text-align: center;
  .content-Centeritem {
    display: flex;
    .content-Centeritem-right {
      a {
        margin: 0 20px;
      }
    }
  } 
  .content-item {
    display: flex;
  }
}
</style>
