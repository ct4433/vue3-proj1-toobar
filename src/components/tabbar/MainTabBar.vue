<template>
  <TabBar>
    <TabBarItem path="/home" activeColor="deepPink">
      <template v-slot:item-icon>
        <img slot="item-icon" src="~assets/img/tabbar/home.png" alt="" />
      </template>
      <template v-slot:item-icon-active>
        <img
          slot="item-icon-active"
          src="~assets/img/tabbar/home_active.png"
          alt=""
        />
      </template>
      <template v-slot:item-text>
        <div slot="item-text">首页</div>
      </template>
    </TabBarItem>

    <TabBarItem path="/category" activeColor="deepPink">
      <template v-slot:item-icon>
        <img slot="item-icon" src="~assets/img/tabbar/categories.png" alt="" />
      </template>
      <template v-slot:item-icon-active>
        <img
          slot="item-icon-active"
          src="~assets/img/tabbar/categories_active.png"
          alt=""
        />
      </template>
      <template v-slot:item-text>
        <div slot="item-text">分类</div>
      </template>
    </TabBarItem>

    <TabBarItem path="/cart" activeColor="deepPink">
      <template v-slot:item-icon>
        <img slot="item-icon" src="~assets/img/tabbar/shopcart.png" alt="" />
      </template>
      <template v-slot:item-icon-active>
        <img
          slot="item-icon-active"
          src="~assets/img/tabbar/shopcart_active.png"
          alt=""
        />
      </template>
      <template v-slot:item-text>
        <div slot="item-text">购物车</div>
      </template>
    </TabBarItem>

    <TabBarItem path="/profile" activeColor="deepPink">
      <template v-slot:item-icon>
        <img slot="item-icon" src="~assets/img/tabbar/profile.png" alt="" />
      </template>
      <template v-slot:item-icon-active>
        <img
          slot="item-icon-active"
          src="~assets/img/tabbar/profile_active.png"
          alt=""
        />
      </template>
      <template v-slot:item-text>
        <div slot="item-text">我的</div>
      </template>
    </TabBarItem>
  </TabBar>
</template>

<script>
import TabBar from "components/tabbar/TabBar";
import TabBarItem from "components/tabbar/TabBarItem";
export default {
  components: {
    TabBar,
    TabBarItem,
  },
};
</script>

<style>
</style>