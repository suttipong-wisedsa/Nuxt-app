<template>
  <div class="content">
    <div class="main">
      <h1>ทดสอบ{{ greetingMessage }}</h1>
      <p>{{ data + data }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    greetingMessage: String, // ประกาศชนิดข้อมูลที่ส่งมาจาก porps
    data: Number,
  },
};
</script>

<style scoped>
h1 {
  color: black;
}
.content {
  display: flex;
  background-color: antiquewhite;
  width: 100%;
  max-width: 800px;
}
.main {
  background-color: aquamarine;
}
</style>