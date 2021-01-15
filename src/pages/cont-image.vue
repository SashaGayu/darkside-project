<template>
<div class="bg-img">
  <img src="../img/970x647/01.jpg" class="bg-img-pd">
  <img src="../img/970x647/03.jpg" class="bg-img-pd">
</div>
</template>

<script>
export default {
name: "cont-image"
}
</script>

<style scoped>
.bg-img {
  padding-top: 100px;
  display: flex;
  justify-content: center;
  flex-direction: row;
}

.bg-img-pd {
  display: block;
  max-width: 100%;
  height: 625px;
  padding-right: 4px;

}
</style>