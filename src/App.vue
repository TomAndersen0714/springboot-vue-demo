<template>
  <div>
    <Header/>
    <!--    <router-link to="/">Home</router-link> |-->
    <!--    <router-link to="/about">About</router-link>-->

    <div style="display: flex">
      <SideMenu></SideMenu>
    </div>
  </div>
  <router-view/>
</template>

<style>

</style>

<script>
import Header from "@/components/Header.vue";
import SideMenu from "@/components/SideMenu.vue";

export default {
  name: "Layout",
  components: {
    Header,
    SideMenu
  }
}
</script>
