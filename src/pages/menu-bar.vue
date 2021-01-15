<template>
<div class="bg">
  <div class="container">
    <div class="service">
      <div class="service-info">
        <a href="#">
          <i class="fas fa-atom"></i>
          <div class="service-text">
            <h3>Art Of Coding</h3>
            <p>Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
          </div>
        </a>
      </div>
      <div class="service-info-cl">
        <a href="#">
          <i class="fas fa-mobile-alt"></i>
          <div class="service-text">
            <h3 class="service-text-title">Responsive Design</h3>
            <p class="service-text-description" style="color: white">Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
          </div>
        </a>
      </div>
      <div class="service-info">
        <a href="#">
          <i class="fas fa-medal"></i>
          <div class="service-text">
            <h3>Art Of Coding</h3>
            <p>Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
          </div>
        </a>
      </div>
    </div>
    <div class="service-2">
      <div class="service-info">
        <a href="#">
          <i class="fas fa-book"></i>
          <div class="service-text">
            <h3>Useful Documentation</h3>
            <p>Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
          </div>
        </a>
      </div>
      <div class="service-info">
        <a href="#">
          <i class="fas fa-tachometer-alt"></i>
          <div class="service-text">
            <h3>Fast Delivery</h3>
            <p>Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
          </div>
        </a>
      </div>
      <div class="service-info">
        <a href="#">
          <i class="fas fa-car-battery"></i>
          <div class="service-text">
            <h3>Free Plugins</h3>
            <p>Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
          </div>
        </a>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "menu-bar"
}
</script>

<style scoped>
.container {
  padding-top: 100px;
  padding-bottom: 100px;
}

.bg {
  width: 100%;
  background: #fafafa!important;
}

.service-info {
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 380px;
  height: 250px;
  background-color: white;
  width: calc((100% - 7px)/3);
}

.service-info-cl {
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 380px;
  height: 250px;
  background-color: #17bed2;
  color: white;
  width: calc((100% - 7px)/3);
}

.service {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.service-text-title {
  color: white;
}

service-text-description {
  color: white;
}

.service-2 {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding-top: 6px;
}

.fas {
  color: #a6a7aa;
  font-size: 30px;
  padding-left: 60px;
  padding-bottom: 20px;
}

.fa-mobile-alt {
  color: white;
  font-size: 30px;
  padding-left: 60px;
  padding-bottom: 20px;
}

.service-text {
  width: 350px;
  padding-left: 60px;
}

</style>