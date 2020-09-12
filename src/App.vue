<!--
 * @Author: your name
 * @Date: 2020-09-12 10:30:14
 * @LastEditTime: 2020-09-12 11:10:30
 * @LastEditors: your name
 * @Description: In User Settings Edit
 * @FilePath: \project\clownwm\src\App.vue
-->
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="努力学习"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
