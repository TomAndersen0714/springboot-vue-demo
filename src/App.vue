<template>
  <nav>
    <Header/>
    <!--    <router-link to="/">Home</router-link> |-->
    <!--    <router-link to="/about">About</router-link>-->

  </nav>
  <router-view/>
</template>

<style>

</style>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "Layout",
  components: {
    Header
  }
}
</script>
