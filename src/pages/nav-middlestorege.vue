<template>
  <div class="banner">
    <div class="promo-block">
      <h1 class="promo-block-title">Digital Product Agency.</h1>
      <p class="promo-block-text">Look no further. You came to the right ... place</p>
      <a href="#" class="btn-theme button"><i class="fas fa-play"></i>WATCH INTRO VIDEO</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "nav-middlestorege"
}
</script>

<style scoped>
.banner {
  position: relative;
  z-index: 2;
  background: url("../img/1920x1080/01.jpg") center center no-repeat;
  background-size: cover;
  width: 100%;
  height: 699px;
}

.banner:after {
  position: absolute;
  z-index: -1;
  background: rgba(81, 87, 105, .4);
  top: 0;
  width: 100%;
  height: 100%;
  left: 0;
  content: " ";
}

.promo-block {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  width: 100%;
  height: 100%;
  z-index: 1;
}

.promo-block-title {
  font-size: 70px;
  color: #fff;
}

.promo-block-text {
  font-size: 25px;
  color: #fff;
  padding-bottom: 20px;
}

.button {
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
  font-size: 15px;
  font-weight: 500;
  padding: 20px 30px;
  font-family: Hind,sans-serif;
}

.button {
  background-color: white;
  color: #515769;
}
.button:hover {
  background-color: #17bed2;
  color: white;
}

.fas {
  margin-right: 15px;
}

</style>