<template lang='pug'>
#app
    div 路由列表：
    router-link(to='/') sql-formatter
    <br/>
    router-link(to='/hello') hello
    div ----下面是内容-----
    <router-view/>
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
}
</style>
