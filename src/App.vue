<template>
  <div id="app">
    <p>老师1222</p>
   <router-view />
    <div>
    <ul>
      <li>小明</li>
      <li>小张</li>
      <li>小李</li>
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
