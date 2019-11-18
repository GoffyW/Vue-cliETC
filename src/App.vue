<!--页面入口文件-->
<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<!--页面解析-->
<!--<template></template> 标签包裹的内容：这是模板的HTMLDom结构-->
<!--<script></script>     标签包括的js内容：你可以在这里写一些页面的js的逻辑代码-->
<!--<style></style>       标签包裹的css内容：页面需要的CSS样式-->
