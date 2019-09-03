<template>
  <div id="app">
    <p>老师1222</p>
   <router-view />
    <div>
    <ul>
      <li>小明222</li>
      <li>小张hjgfff</li>
      <li>小李hjhfff</li>
    </ul>
  </div>
  </div>
  
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
#app {
  text-align: center;
  margin-top: 60px;
}
ul{
  list-style:none;
}
</style>
