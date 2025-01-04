<template>
  <div id="app">
    <!-- 路由占位符 -->
    <router-view></router-view>
    <div>
      <img
          src="https://milkbeer.cn/weixin.png"
          style="height: 100px; width: 100px"
      />
      <span slot="reference"> 联系作者|   ©2025-2026 By YY </span>
      <a href="https://beian.miit.gov.cn">&nbsp;&nbsp;备案号:浙ICP备2025144000号-1</a>
      <!--
      <br />
            <a href="https://beian.mps.gov.cn/#/query/webSearch">
              <img
                  src="https://xxx.xiaobaitiao.icu/img/icu/202312211243636.png"
                  style="height: 16px; width: 16px; margin: 5px 0px 0px 5px"
              />
              浙公网安备33028202001002号
            </a>
      -->
    </div>
  </div>
</template>

<script>


export default {
  name: 'app',
  
}
</script>

<style>

</style>
