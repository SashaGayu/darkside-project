<template>
<div class="deepcont">
  <div class="container">
    <div class="parralax-title">
      <h2 class="d-block-size">Displaying the Result</h2>
      <p class="d-block-size-pd">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo.</p>
    </div>
  </div>

  <div class="parallax"></div>
  <div class="prlx">
    <div class="article_table">
      <div class="image_table">
        <div class="image_table_up">
          <div class="image-size btn-img-padding-m1"><img src="../img/800x400/01.jpg" alt="img"></div>
          <div class="image-size"><img src="../img/397x400/01.jpg"></div>
        </div>
        <div class="image_table_bottom">
          <div class="image-size"><img src="../img/397x300/01.jpg"></div>
          <div class="image-size btn_img_padding-m2"><img src="../img/397x300/02.jpg" class="image-width-size"></div>
          <div class="image-size"><img src="../img/397x300/03.jpg"></div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
}
</script>

<style scoped>
body, html {
  height: 100%;
}

.image-size  {
  height: 100%;
  width: 100%;
  position: relative;
  z-index: 2;
}

.image-size:after {
  position: absolute;
  z-index: 1;
  cursor: pointer;
  content: " ";
  top: 0;
  width: 100%;
  height: 100%;
  left: 0;
  transition: all 0.3s;
  background-color: rgba(0,0,0,.5);
  opacity: 0;
}

.image-size:hover:after {
  opacity: 1;
}


.image-width-size {
  width: 399px;
  height: 300px;
}

.btn-img-padding-m1 {
  margin-right: 4px;
}

.btn_img_padding-m2 {
  margin-left: 4px;
  margin-right: 4px;
}

.article_table {
  display: flex;
  justify-content: center;
}

.image_table_up {
  display: flex;
  flex-direction: row;
  padding-bottom: 4px;
}

.image_table_bottom {
  display: flex;
  flex-direction: row;
}

.deepcont {
  background-image: url('../img/1920x1080/02.jpg');
  height: 100%;
  width: 100%;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  z-index: 2;
  background-size: cover;
}

.deepcont:after {
  position: absolute;
  z-index: -1;
  background: rgba(81, 87, 105, .4);
  top: 0;
  width: 100%;
  height: 100%;
  left: 0;
  content: " ";
}


@media only screen and (max-device-width: 1366px) {
  .parallax {
    background-attachment: scroll;
  }
}

.prlx {
  padding-top: 100px;
  padding-bottom: 100px;
  background-color:white;
  text-align: center;
}


.container {
  height: 390px;
}

.d-block-size {
  font-size: 50px;
  color: white;
}

.d-block-size-pd {
  font-size: 20px;
  color: #fff;
  opacity: .8;
}

.parralax-title {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  height: 390px;
}

</style>