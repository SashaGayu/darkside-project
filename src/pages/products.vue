<template>
<div class="container">
  <div class="content">
    <h2 class="text-size">Latest Products</h2>
    <p class="content-size">Lorem ipsum dolor sit amet consectetur adipiscing elit sed tempor incididunt ut laboret dolore magna aliqua enim minim veniam exercitation</p>
  </div>
  <div class="card-block">
      <div class="card-block-info">
        <img src="../img/970x647/01.jpg" alt="Avatar" class="card-img">
          <div class="card-text">
            <h4><b>John Doe<span class="text-uppercase">MANAGEMENT</span></b></h4>
            <p>Lorem ipsum dolor sit amet consectetur adipiscing elit sed tempor incdidunt ut laboret dolor magna ut consequat siad esqudiat dolor</p><a href="#" class="link">READ MORE</a>
            <a href="#" class="link"></a>
          </div>
      </div>
      <div class="card-block-info">
        <img src="../img/970x647/02.jpg" alt="Avatar" class="card-img">
          <div class="card-text">
            <h4><b>John Doe<span class="text-uppercase">DEVELOPMENY</span></b></h4>
            <p>Lorem ipsum dolor sit amet consectetur adipiscing elit sed tempor incdidunt ut laboret dolor magna ut consequat siad esqudiat dolor</p>
            <a href="#" class="link">READ MORE</a>
          </div>
      </div>
      <div class="card-block-info">
        <img src="../img/970x647/03.jpg" alt="Avatar" class="card-img">
          <div class="card-text">
            <h4><b>John Doe<span class="text-uppercase">DESIGN</span></b></h4>
            <p>Lorem ipsum dolor sit amet consectetur adipiscing elit sed tempor incdidunt ut laboret dolor magna ut consequat siad esqudiat dolor</p>
            <a href="#" class="link">READ MORE</a>
          </div>
      </div>
  </div>
</div>
</template>

<script>
export default {
name: "products",
}
</script>

<style scoped>

.content {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  padding-top: 100px;
}

.content-size {
  width: 555px;
  text-align: center;
  padding-bottom: 40px;
}

.text-size {
  padding-bottom: 15px;
  font-size: 30px;
}

.card-img {
  width: 100%;
}

.card-block-info {
  width: calc((100% - 40px)/3);
}

.text-uppercase {
  margin-left: 20px;
}

.card-block-info:last-child {
  padding-right: 0;
}

.card-block {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.card-text {
  padding-top: 15px;
}
</style>