<template>
  <!--html-->
  <div class="app">
    <h1>你好啊！</h1>
    <person />
  </div>
</template>

<script lang="ts">
import Person from "./components/Person.vue";
// Js或TS
export default {
  name: "App", //组件名
  components: { Person }, //注册组件
};
</script>

<style>
/*样式*/
.app {
  background-color: aqua;
  box-shadow: 0 0 10px;
  border-radius: 20px;
  padding: 20px;
}
</style>
