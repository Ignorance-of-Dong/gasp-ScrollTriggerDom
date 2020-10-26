<!--
 * @Author: zhangzheng
 * @Date: 2020-10-22 17:31:35
 * @LastEditors: zhangzheng
 * @LastEditTime: 2020-10-26 11:44:39
 * @Descripttion: 
-->
<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
