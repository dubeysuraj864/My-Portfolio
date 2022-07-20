<template>
  <div class="footer">
    <div class="title">Contact Me</div>
    <div class="para">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, recusandae
      sed est atque eveniet iste suscipit nihil itaque commodi minima.
    </div>
    <div class="button">
      <button id="contact" class="fill">
        <a href="https://www.linkedin.com/in/suraj-dubey-a1baa3202/"
          >Contact Me Now</a
        >
      </button>
    </div>
  </div>
  <div class="foot">
    <div class="by">Suraj Dubey — Copyright 2022</div>
    <div class="social">
      <a href="https://www.instagram.com/dubeysuraj864/" target="_blank"><img src="../assets/instagram.png" alt="social" class="social-icon"></a>
      <a href="https://www.linkedin.com/in/suraj-dubey-a1baa3202/" target="_blank"><img src="../assets/linkedin-logo.png" alt="social" class="social-icon"></a>
      <a href="https://twitter.com/dubeysuraj864" target="_blank"><img src="../assets/twitter-sign.png" alt="social" class="social-icon"></a>
      <a href="https://github.com/dubeysuraj864" target="_blank"><img src="../assets/github-sign.png" alt="social" class="social-icon"></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "foot-er",
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  user-select: none;
}
.footer {
  text-align: center;
  width: auto;
  height: 70vh;
  color: rgb(0, 0, 0);
  background-color: rgb(225, 225, 225);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.title {
  font-size: 10vw;
  font-weight: bold;
}
.para {
  font-size: 1.2vw;
  width: 50vw;
  margin: 1vw 0vw;
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
  background: linear-gradient(to right, #63e8ea, #ffd025);
  border-radius: 0.1vw;
  border: none;
  outline: none;
  font-style: normal;
  font-weight: 500;
  font-size: 1.2vw;
  cursor: pointer;
}
#contact a {
  text-decoration: none;
  color: rgb(255, 255, 255);
}

.foot {
  text-align: center;
  width: 100%;
  background-color: rgb(255, 255, 255);
  color: #000;
  padding: 1vw;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.by {
  font-size: 1vw;
  /* padding: 2vw 2vw 0vw 2vw; */
}
.social a {
  color: skyblue;
  font-size: 1vw;
  font-weight: 600;
  margin: 1vw 1vw;
}
.social-icon{
  width: 1.5vw;
  height:1.5vw;
}
/* --------------------------------------------- */

@media (max-width: 600px) {
  .footer {
    border-radius: 20% 20% 0% 0%;
    background: linear-gradient(
      to bottom,
      rgb(100, 255, 190),
      rgb(100, 203, 255)
    );
    height: 50vh;
    color: white;
  }
  .title {
    font-size: 10vw;
    font-weight: bold;
  }
  .para {
    font-size: 4.2vw;
    width: 80vw;
    margin: 1vw 0vw;
  }
  #contact {
    font-size: 5.2vw;
    padding: 5vw 5vw;
    margin-top: 5vw;
    margin-bottom: 5vw;
    background: rgba(255, 255, 255, 0.2);
    color: rgb(255, 255, 255);
  }
  #contact:hover {
    background: rgba(255, 255, 255, 0.2);
  }

  .foot {
    text-align: center;
    width: 100%;
    background-color: rgb(255, 255, 255);
    padding: 5vw;
    flex-direction: column-reverse;
  }
  .by {
    font-size: 3vw;
    padding: 5vw 2vw 0vw 2vw;
  }
  .social a {
    color: skyblue;
    font-weight: 600;
    margin: 2vw 2vw;
  }
  .social-icon{
  width: 8.5vw;
  height: 8.5vw;
}
}
</style>
