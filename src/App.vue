<template>
      <header class="appbar mdui-appbar mdui-appbar-fixed">
  <div class="mdui-toolbar mdui-color-theme">
    <span
      class="mdui-btn mdui-btn-icon mdui-ripple mdui-ripple-white"
      mdui-drawer="{target: '#drawer', swipe: true}"
    >
      <i class="mdui-icon material-icons">menu</i>
    </span>
    <a href="./" class="mdui-typo-headline">Wmz1024</a>
    <a href="./" class="mdui-typo-title mdui-hidden-xs">主页</a>
    <div class="mdui-toolbar-spacer"></div>
  </div>
</header>
<ToolBar></ToolBar>
  <router-view />
</template>

<script>
import ToolBar from './components/ToolBar.vue';
export default {
  name: 'App',
  components: {
    ToolBar,
}
}
</script>