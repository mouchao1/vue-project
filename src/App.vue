<template>
  <div id="app">
    <h1 v-html="title"></h1>
    <h2 v-text="msg"></h2>
  </div> 
</template>

<script>
export default {
  data () {
    return {
      title: '武汉理工大学信息管理与信息系统',
      msg:'<王靖超 信管1603班>'
    }
  },
  methods(){
    
  },
  watch(){
    
  }
}
</script>

<style>
html{
  height: 100%;
}
body{
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
#app {
  display: flex;
  justify-content:center;
  flex-direction:column;
  align-items:center;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
