<template>
  <div id="app">
    <Navbar id="navbar" />
    <ContainerMain id="container-main" />
    <FeaturedWork id="featured-work" />
    <FooterMain />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import ContainerMain from "./components/ContainerMain.vue";
import FeaturedWork from "./components/FeaturedWork.vue";
import FooterMain from "./components/FooterMain.vue";
export default {
  name: "App",
  components: {
    Navbar,
    ContainerMain,
    FeaturedWork,
    FooterMain,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Arvo:wght@400;700&family=Lato:wght@300;400;900&family=Poppins:wght@100;200;300;400;500&family=Potta+One&display=swap");
#app {
  font-family: "Poppins", sans-serif;
  backdrop-filter: blur(2em);
  user-select: none;
  width: 100%;
  height: 70vh;
  color: #fff;
}
img {
  -webkit-user-drag: none;
  -khtml-user-drag: none;
  -moz-user-drag: none;
  -o-user-drag: none;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  user-select: none;
  scroll-behavior: smooth;
  /* -webkit-transition: all 300ms ease; */
}
</style>
