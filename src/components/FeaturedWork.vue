<template>
  <main>
    <div class="title"><span>Featured Work</span></div>
    <div class="work">
      <div class="group-work">
        <div class="box1 box"><img src="https://blog.spoongraphics.co.uk/wp-content/uploads/2015/11/thumbnail9.jpg" alt=""></div>
        <div class="box2 box"><img src="https://www.vectornator.io/blog/content/images/2022/05/611ab4846fca351648d90674_Cover-Vector-Art.png" alt=""></div>
        <div class="box3 box"><img src="https://3.bp.blogspot.com/-K0n-CdbmUx0/XDS7ZYNjg7I/AAAAAAAAAXI/zQXLcbby8Q4A-UqFyXlyNkun04VId-dDQCLcBGAs/s1600/HRMonochromatic_End.JPG" alt=""></div>
        <div class="box4 box"><img src="https://miro.medium.com/max/1400/0*jy-UfPAGQd_FN9QN.png" alt=""></div>
        <div class="box5 box"><img src="https://i.pinimg.com/originals/14/2b/05/142b059a8ca0f6c3097ddf75aa7207a1.png" alt=""></div>
        <div class="box6 box"><img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/78775d76358541.5c670847b25f2.jpg" alt=""></div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "featured-work",
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  
}

main{
    padding: 2vw 0vw;
      color: #000;
      text-align: center;
}

.title{
    font-size: 3vw;
    margin: 2vw 0vw;
    
}
.title span{
    border-bottom: .5vw solid #000;
    width: fit-content;
}

.work {

  font-family: "Poppins", sans-serif;
  display : flex;
  justify-content: center;
 
}
.group-work {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  
}
.box {
  margin: 1vw;
}
.box img{
      border: .4vw solid #fff;
    transition: all 300ms ease;
    object-fit: cover;
    cursor: pointer;
     width: 20vw;
  height: 20vw;
    box-shadow: .2vw .4vw 1vw rgba(0, 0, 0, 0.25);
}
.box img:hover{

    box-shadow: none;
    }
</style>
