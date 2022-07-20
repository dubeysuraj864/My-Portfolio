<template>

    <div class="container">
      <div class="left">
        <div class="myself">
          Hi, I am Suraj <br />
          A Front-End Developer <br />
          based in Delhi, India.
          <div class="intro">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br />
          Est, posuere ultrices viverra enim sit urna tempor <br />
          pellentesque.
        </div>
          <div class="button">
            <button id="contact" class="fill"><a style="text-decoration: none;   color: rgb(255, 255, 255);" href="https://www.linkedin.com/in/suraj-dubey-a1baa3202/"> Contact Me Now</a></button>
          </div>
        </div>
      </div>
      <div class="right">
        <img src="../assets/me-cutout.png" alt="" />
      </div>
      <!-- <div class="icons">
        <img src="../assets/html-5.png" class="html" alt="icon">
        <img src="../assets/css-3.png" class="css" alt="">
        <img src="../assets/js.png" class="js" alt="">
        <img src="../assets/physics.png" class="react" alt="">
        <img src="../assets/vue.png" class="vue" alt="">
        <img src="../assets/sass.png" class="sass" alt="">
        <img src="../assets/github-sign.png" class="github" alt="">
        <img src="../assets/java.png" class="java" alt="">
      </div> -->
    </div>
</template>

<script>

export default {
  name: "container-main",

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
.container {
  font-family: "Poppins", sans-serif;
    background: linear-gradient(to right, #63e8ea, #ffd025);
  display: flex;
  justify-content: space-around;
  flex-direction: column;
  align-items: center;
  width: 100%;
  height: 43.6vw;
  position: relative;
  
}
.left {
  margin-top: 5vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  position: absolute;
  left: 12vw;
}
.myself {
  font-size: 4vw;
  font-weight: bold;
  line-height: 4.4vw;
}
.intro {
  width: 40vw;
  font-weight: 400;
  font-size: 1.2vw;
  line-height: 1.5vw;
  letter-spacing: -0.05vw;
  color: #fffbfb;
  margin-top: 1vw;
}
#contact {
  transition: all 300ms ease;
  font-family: "Poppins", sans-serif;
  margin-top: 1vw;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 1vw 3vw;
  gap: 1vw;
  background: rgba(255, 255, 255, 0.2);
  color: rgb(255, 255, 255);
  /* box-shadow: 0.2vw 0.4vw 1vw rgba(0, 0, 0, 0.25); */
  border-radius: 0.1vw;
  outline: none;
  font-style: normal;
  font-weight: 500;
  font-size: 1.2vw;
  cursor: pointer;
  border: none;
}
#contact img{
  width: 1.5vw;
  height: 1.9vh;
}
#contact:hover {
  transition: all 300ms ease;
  color: rgb(255, 255, 255);
  background: rgba(255, 255, 255, 0.341);
    box-shadow: none;
}
.right {
  position: absolute;
  right: 10vw;
}
.right img {
  width: 44vw;
  height: 44vw;
}
.icons{
  position: absolute;
}
.icons img{
  z-index: 3;
  width: 5vw;
  height : auto;
}
.html{
    position: absolute;
      top: -30vh;
    right: -10vw;
}
.css{
    position: absolute;
     top: -20vh;
    right: -0vw;
}
.js{
    position: absolute;
    top: -40vh;
    right: -20vw;
}
.react{
    position: absolute;
      top: -30vh;
    right: -35vw;
}
.vue{
    position: absolute;
    top: -20vh;
    right: -45vw;
}
.sass{
    position: absolute;
    top: 10vh;
    right: -30vw;
}
.github{
    position: absolute;
    top: -8vh;
    right: -40vw;
}
.java{
    position: absolute;
    top: -40vh;
    right: -30vw;
}
/* --------------------------------------------- */

@media (max-width: 600px) {
  .container {
    height: 82.6vh;
    flex-direction: column;
 background: linear-gradient(to bottom, #63e8ea, #ffd025);
  }
.intro{
  display: none;
}
  .left {
    position: absolute;
    top: 10vh;
    left: 0vw;
  }
  .myself {
    text-align: center;
    width: 100vw;
    font-size: 8vw;
    line-height: 10.4vw;
    position: absolute;
    top: 0vh;
    left: 0vw;
  }
  #contact {
    font-size: 6.2vw;
    margin-top: 5vw;
    position: absolute;
    /* top: 50.6vh; */
    left: 21vw;
      /* border: 1vw solid #fff; */
        padding: 3vw 6vw;
        color: rgb(255, 255, 255);
        box-shadow: none;
   }
  .right {
    -webkit-transform: scaleX(-1);
    transform: scaleX(-1);
    position: absolute;
    top: 34vh;
    right: 0vw;
    
  }
  .right img {
    width: 104vw;
    height: 103.5vw;

  }
}
</style>
