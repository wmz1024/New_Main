<template>
  <div>
    <RouterView>
     <div class="mdui-drawer" id="drawer">
    <ul class="mdui-list">
        <router-link to="/">
      <li class="mdui-list-item mdui-ripple">
        <i class="mdui-list-item-icon mdui-icon material-icons">folder</i>
        <div class="mdui-list-item-content">主页</div>
      </li></router-link>
              <router-link to="/About">
      <li class="mdui-list-item mdui-ripple">
        <i class="mdui-list-item-icon mdui-icon material-icons">folder</i>
        <div class="mdui-list-item-content">关于</div>
      </li></router-link>
    </ul>
  </div>
  </RouterView>
  </div>
</template>
