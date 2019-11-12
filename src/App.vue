<template>
  <div id="app">
    <van-nav-bar
    title="范特西体育"
    fixed
    class="nb"
    />
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
  background-color: black;
  margin-top: 60px;
}
.nb{
  color: #ffffff;
  background-color: black;
}
</style>
