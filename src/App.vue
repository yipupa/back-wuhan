<template>
  <div id="app">
    <x-header :left-options="{showBack: false}">返汉人员在线申报系统</x-header>
    <router-view></router-view>
  </div>
</template>

<script>
import {
  XHeader
} from 'vux'
export default {
  name: 'app',
  components: { XHeader }
}
</script>

<style lang="less">
@import '~vux/src/styles/reset.less';

body {
  background-color: #fbf9fe;
}
</style>
