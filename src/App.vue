<template>
  <div id="app">
    <keep-alive exclude="Detail">
      <!-- 当前路由地址所显示的内容 -->
      <router-view/>
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
</style>

// 路由就是根据网址的不同，返回不同的内容给用户
