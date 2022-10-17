<!-- Please remove this file from your project -->
<template>
  <div>
    <Nav />
    <Content greeting-message="hello" data="5" />
    <!-- ส่งค่า props ไปที่ content  -->
  </div>
</template>
<style scoped>
body {
  margin: 0;
}
</style>
<script>
import Content from "./Content.vue"; //import component
import Nav from "./Nav.vue";
export default [
  {
    //import component
    name: "NuxtTutorial",
    components: { Content },
  },
  {
    name: "Nav",
    components: { Nav },
  },
];
</script>
