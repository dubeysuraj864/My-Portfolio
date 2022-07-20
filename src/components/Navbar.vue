<template>
  <div class="navbar">
    <nav>
      <div class="logo">
       XD
        <!-- <img src="../assets/logo.png" alt=""> -->
        </div>
      <div class="menu">
        <MenuBar />
      </div>
      <div class="navlinks">
        <a href="#">Home</a> <a href="#">Recent Work</a>
        <a href="#">Contact Me</a>
        <a href="#">About Me</a>
      </div>
    </nav>
  </div>
</template>

<script>
import MenuBar from "./MenuBar.vue";
export default {
  name: "nav-bar",
  components: {
    MenuBar,
  },
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  user-select: none;
  -webkit-user-select: none;
}
.logo {
  display: flex;
  justify-content: space-around;
  align-items: center;
  font-size: 2.5vw;
  font-weight: bold;
}.logo img{
  width: 5vw;
  height: 5vw;
}
a {
  text-decoration: none;
  font-size: 1.2vw;
  font-weight: 400;
  margin: 0.7vw;
  color: rgb(255, 255, 255);
  transition: all 300ms ease;
}
a:hover{
   color: rgba(255, 255, 255, 0.598);
}
nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  color: rgb(255, 255, 255);
  background-color: rgba(255, 255, 255, 0.293);
  padding: 1vw;
  backdrop-filter: blur(1vw);
}
.navbar {
  position: relative;
  background: linear-gradient(to right, #63e8ea, #ffd025);
}
.menu {
  display: none;
}

/* --------------------------------------------- */

@media (max-width: 600px) {
  .menu {
    display: inline-block;
    position: absolute;
    top: 0vh;
    left: 0vw;
    
  }
  .logo {
    position: absolute;
    top: 2vh;
    left: 80vw;
    font-size: 7.5vw;
  }
  a {
    font-size: 5vw;
  }
  .navlinks {
    display: none;
  }
  nav {
    position: absolute;
    background-color: rgba(181, 181, 181, 0);
  }
  .navbar {
    z-index: 2;
    background: linear-gradient(to top, #63e8ea, #25ff9999);
  }
  .logo img{
  width: 20vw;
  height: 20vw;
}
}
</style>
