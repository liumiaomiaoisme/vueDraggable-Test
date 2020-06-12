<!--
 * @Author: your name
 * @Date: 2020-06-08 22:08:09
 * @LastEditTime: 2020-06-08 23:00:09
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \formtest\src\App.vue
--> 
<template>
  <div id="app">
    <draggable />
    <el-alert>基于Vue+ElementUI制作一款表单设计器</el-alert>
    <draggable-advance />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Draggable  from './components/Draggable.vue'
import DraggableAdvance  from './components/DraggableAdvance.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld,
    Draggable,
    DraggableAdvance

  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
