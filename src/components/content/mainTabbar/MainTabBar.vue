<template>
  <tab-bar>
    <tab-bar-item path="/home">
      <img src="~assets/img/tabbar/shouye.png" slot="item-icon" />
      <img src="~assets/img/tabbar/shouye2.png" slot="item-icon-active" />
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <img src="~assets/img/tabbar/fenlei.png" slot="item-icon" />
      <img src="~assets/img/tabbar/fenlei2.png" slot="item-icon-active" />
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img src="~assets/img/tabbar/gouwuchekong.png" slot="item-icon" />
      <img src="~assets/img/tabbar/gouwuchekong2.png" slot="item-icon-active" />
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img src="~assets/img/tabbar/wode.png" slot="item-icon" />
      <img src="~assets/img/tabbar/wode2.png" slot="item-icon-active" />
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
import TabBar from "components/common/tabbar/Tabbar";
import TabBarItem from "components/common/tabbar/Tabbaritem";

export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem,
  },
};
</script>

<style>
</style>
