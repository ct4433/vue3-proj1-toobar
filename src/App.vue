<template>
  <div>
    <router-view></router-view>
    <MainTabBar></MainTabBar>
  </div>
</template>

<script>
import MainTabBar from "./components/tabbar/MainTabBar";
export default {
  components: {
    MainTabBar,
  },
};
</script>


<style>
@import "./assets/css/base/base.css";
</style>