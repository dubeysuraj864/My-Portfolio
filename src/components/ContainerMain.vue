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
          <button id="contact">Contact Me Now</button>
        </div>
      </div>
    </div>
    <div class="right">
      <img src="../assets/me-cutout.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "container-main",
};
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
    font-family: 'Poppins', sans-serif;
    background-image: url("https://images.unsplash.com/photo-1657127791336-c9dd34247f78?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1632&q=80");

  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  object-fit: cover;
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 100%;
  height: 32.6vw;
  backdrop-filter: brightness(90%);
  position: relative;

}
.left {
  margin-top: 7vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  position: absolute;
  left: 15vw;
}
.myself {
  font-size: 3vw;
  font-weight: bold;
  line-height: 3.4vw;
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
    font-family: 'Poppins', sans-serif;
  margin-top: 1vw;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 1vw 13vw;
  gap: 1vw;
  background: rgba(255, 255, 255, 0.36);
  color: #fff;
  box-shadow: .2vw .4vw 1vw rgba(0, 0, 0, 0.25);
  backdrop-filter: blur(1vw);
  border-radius: .1vw;
  border: .2vw solid #fff;
  outline: none;
  font-style: normal;
  font-weight: 600;
  font-size: 1vw;
}
.right {
  position: absolute;
  right: 10vw;
  
}
.right img {
  width: 33vw;
  height: 33vw;
  
  /* transf */
}
</style>
