<template>
  <div id="app">
    <!-- 使用keep-alive 只发送一次ajax请求，数据将缓存到内存中，提高性能 exclude指Detail不缓存-->
    <keep-alive exclude="Detail">
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
