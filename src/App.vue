<template>
  <div>
    <Home/>
  </div>
</template>

<script>
import Home from "@/Home"

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>

body {
  margin: 0;
  padding: 0;
}

.container {
  width: 1170px;
}


html {
  overflow-x: hidden;
}

html, html a, body {
  -webkit-font-smoothing: antialiased;
}

body {
  position: relative;
  font-family: Hind, sans-serif;
}

p {
  font-size: 15px;
  font-weight: 400;
  font-family: Hind, sans-serif;
  color: #a6a7aa;
  line-height: 1.4;
  margin-bottom: 15px;
}

em,
li,
li a {
  font-size: 16px;
  font-weight: 500;
  font-family: Hind, sans-serif;
  color: #515769;
}

a {
  font-family: Hind, sans-serif;
  color: #81848f;
  outline: 0;
  text-decoration: none;
}

a:focus, a:hover, a:active {
  outline: 0;
  color: #999caa;
  text-decoration: none;
}

.link {
  position: relative;
  font-size: 13px;
  font-weight: 600;
  font-family: Hind, sans-serif;
  text-transform: uppercase;
}

.link:after {
  position: absolute;
  top: 8px;
  right: -15px;
  width: 9px;
  height: 2px;
  background: #17bed2;
  content: " ";
}

span {
  font-size: 14px;
  font-weight: 400;
  font-family: Hind, sans-serif;
  color: #bfc1c7;
}

h1, h2, h3, h4, h5, h6 {
  font-weight: 700;
  font-family: Hind, sans-serif;
  color: #515769;
  line-height: 1.4;
  margin: 0 0 15px;
}

.pricing .pricing-list-item:before {
  position: absolute;
  top: 7px;
  left: 0;
  width: 9px;
  height: 2px;
  background: #17bed2;
  margin-right: 10px;
}

h1 > a, h2 > a, h3 > a, h4 > a, h5 > a, h6 > a {
  color: #515769;
}

h1 > a:hover, h2 > a:hover, h3 > a:hover, h4 > a:hover, h5 > a:hover, h6 > a:hover {
  color: #999caa;
  text-decoration: none;
}

h1 > a:focus, h2 > a:focus, h3 > a:focus, h4 > a:focus, h5 > a:focus, h6 > a:focus {
  text-decoration: none;
}

h1 {
  font-size: 40px;
}

h2 {
  font-size: 30px;
}

h3 {
  font-size: 22px;
}

h4 {
  font-size: 22px;
}

::selection {
  color: #fff;
  background: #17bed2;
  text-shadow: none;
}

::-webkit-selection {
  color: #fff;
  background: #17bed2;
  text-shadow: none;
}

::-moz-selection {
  color: #fff;
  background: #17bed2;
  text-shadow: none;
}

:active,
:focus {
  outline: none;
}

</style>
