<template>
  <div>
    <nav-bar/>
    <nav-middle/>
    <products/>
    <cont-image/>
    <menu-bar/>
    <effect-prestige/>
    <content-lg/>
  </div>
</template>

<script>
import NavBar from "@/pages/nav-bar"
import NavMiddle from "@/pages/nav-middlestorege"
import Products from "@/pages/products"
import ContImage from "@/pages/cont-image"
import MenuBar from "@/pages/menu-bar"
import EffectPrestige from "@/pages/effectprestige"
import ContentLg from "@/pages/content-lg"

export default {
  name: "Home",
  components: {
    NavBar,
    NavMiddle,
    Products,
    ContImage,
    MenuBar,
    EffectPrestige,
    ContentLg
  }
}
</script>

<style scoped>

</style>