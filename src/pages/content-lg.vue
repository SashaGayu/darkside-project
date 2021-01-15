<template>
<div class="bg-clr">
  <div class="container">
    <div class="pricing">
      <div class="pricing_selector">
        <i class="fas fa-medal"></i>
        <h3>Professional <span>- $</span> 149</h3>
        <p class="descriprion-size">Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
        <div class="link">Basic Features</div>
        <div class="link">Basic Features</div>
        <div class="link btn-chose">Basic Features</div>
        <div class="button btn-chose">CHOSE</div>
      </div>
      <div class="pricing_selector big_selector">
        <i class="fas fa-medal"></i>
        <h3>Professional <span>- $</span> 149</h3>
        <p class="descriprion-size">Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
        <div class="link">Basic Features</div>
        <div class="link">Basic Features</div>
        <div class="link btn-chose">Basic Features</div>
        <div class="button btn-chose">CHOSE</div>
      </div>
      <div class="pricing_selector">
        <i class="fas fa-medal"></i>
        <h3>Professional <span>- $</span> 149</h3>
        <p class="descriprion-size">Lorem ipsum dolor amet consectetur ut consequat siad esqudiat dolor</p>
        <div class="link">Basic Features</div>
        <div class="link">Basic Features</div>
        <div class="link btn-chose">Basic Features</div>
        <div class="button">CHOSE</div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
name: "content-lg"
}
</script>

<style scoped>
.bg-clr {
  width: 100%;
  background: #fafafa!important;
}

.descriprion-size {
  width: 285px;
}

.btn-chose {
  padding-bottom: 40px;
}

.pricing_selector {
  padding: 60px 45px;
  background: #fff;
  margin-top: 20px;
}

.big_selector {
  padding-top: 110px;
  padding-bottom: 110px;
  margin-left: 4px;
  margin-right: 4px;
  margin-top: 10px;
}

.button {
  border: none;
  text-align: center;
  text-decoration: none;
  padding-top: 50px;
  height: 48px;
  color: #515769;
  width: 125px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
  padding: 20px 30px;
  font-family: Hind,sans-serif;
  font-size: 13px;
  font-weight: 600;
  position: relative;
}

.button {
  background-color: #fafafa;
  color: #515769;
}
.button:hover {
  background-color: #17bed2;
  color: #fafafa!important;
}

.link {
  display: flex;
  justify-content: flex-start;
  font-weight: 500;
  width: 74%;
  text-transform: none;
  position: relative;
  font-size: 13px;
  color: #81848f;
  padding-left: 17px;
  margin-bottom: 10px;
}

.link:after {
  position: absolute;
  top: 8px;
  left: -3px;
  width: 9px;
  height: 2px;
  background: #17bed2;
  content: " ";
}

.container {
  padding-top: 100px;
  padding-bottom: 100px;
}

.pricing {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.fa-medal {
  color: #a6a7aa;
  font-size: 30px;
  padding-bottom: 40px;
}
</style>