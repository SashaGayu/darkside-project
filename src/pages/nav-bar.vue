<template>
  <div class="header">
    <div class="container">
      <div class="nav-logo">
        <a href="/"><img src="../img/logo.png" alt="logo"></a>
      </div>
      <div class="nav-bar-right">
        <a class="nav-item-child nav-item-hover" href="#body">HOME</a>
        <a class="nav-item-child nav-item-hover" href="#products">PRODUCTS</a>
        <a class="nav-item-child nav-item-hover" href="#service">SERVICE</a>
        <a class="nav-item-child nav-item-hover" href="#work">WORK</a>
        <a class="nav-item-child nav-item-hover" href="#pricing">PRICING</a>
        <a class="nav-item-child nav-item-hover" href="#contact">CONTACT</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "nav-bar"
}
</script>

<style scoped>
.header {
  height: 97px;
  width: 100%;
  border-bottom: 1px solid rgba(255,255,255,.2);
  transition-duration: .3s;
  transition-property: all;
  transition-timing-function: cubic-bezier(.7,1,.7,1);
  position: absolute;
  z-index: 10;

}



.container {
  height: 100%;
  display: flex;
  align-items: center;
}

.nav-bar-right {
  display: flex;
  justify-content: flex-end;
  width: 100%;
}

.nav-item-child:last-child {
  padding-right: 0;
}

.nav-item-child {
  font-size: 13px;
  font-weight: 600;
  color: #fff;
  line-height: 55px;
  padding: 20px;
  transition-duration: .3s;
  transition-property: all;
  transition-timing-function: cubic-bezier(.7,1,.7,1);
}





</style>