<template>
  <div class="layout-wrepper">
    <h2>Galery Foto</h2>
    <div class="item-layout">
      <img src alt />
    </div>
    <div class="item-layout">
      <img src alt />
    </div>
    <div class="item-layout">
      <img src alt />
    </div>
    <div class="item-layout">
      <img src alt />
    </div>
    <div class="item-layout">
      <img src alt />
    </div>
  </div>
</template>

<script>
export default {
  name: "Layout",
};
</script>

<style scoped>
.layout-wrepper {
  width: 70%;
  overflow: hidden;
  margin: auto;
  background: white;
}

.item-layout {
  float: left;
  margin-right: 30px;
  width: 150px;
  height: 150px;
  background: burlywood;
}
</style>