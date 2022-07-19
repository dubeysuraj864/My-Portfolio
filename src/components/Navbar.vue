<template>
  <div class="navbar">
    <nav>
      <div class="logo">Logo</div>
      <div class="navlinks">
        <a href="#">Home</a> <a href="#">Recent Work</a>
        <a href="#">Contact Me</a>
        <a href="#">About Me</a>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "nav-bar",
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
  font-size: 1.5vw;
  font-weight: bold;
}

#contact a{
  text-decoration: none;
  font-size: 1vw;
  font-weight: 500;
  margin: 0.7vw;
  color: rgb(255, 255, 255);
}
nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  color: rgb(255, 255, 255);
  background-color: rgba(181, 181, 181, 0.198);
  padding: 1vw;
  backdrop-filter: blur(1vw);
}
.navbar {
  background-image: url("https://images.unsplash.com/photo-1657127791336-c9dd34247f78?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1632&q=80");

  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  object-fit: cover;
}

/* --------------------------------------------- */

@media (max-width: 600px) {
  .logo {
    font-size: 7.5vw;
  }
  a {
    font-size: 5vw;
  }
  .navlinks {
    display: none;
  }
  nav {
    background-color: rgba(181, 181, 181, 0);
  }
  .navbar {
    background-image: url("https://images.unsplash.com/photo-1655998233171-ee5b130acba5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=699&q=80");
  }
}
</style>
