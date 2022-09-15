<template>
  <main>
    <div class="title"><span>Featured Work</span></div>
    <div class="work">
      <div class="group-work">
        <div class="box1 box">
       
        </div>
        <div class="box2 box">
        
        </div>
        <div class="box3 box">
       
        </div>
        <div class="box4 box">
         
        </div>
        <div class="box5 box">
      
        </div>
        <div class="box6 box">
      
        </div>
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
    user-select: none;
 
}
img{
    -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -o-user-select: none;
  user-select: none;
}
main {
  padding: 2vw 0vw;
  color: #000;
  text-align: center;
  
}

.title {
  font-size: 8vw;
  margin: 1.5vw 0vw;
 
}
.title span {
  border-bottom: 0.5vw solid rgba(0, 0, 0, 0);
  width: fit-content;
}

.work {
  font-family: "Poppins", sans-serif;
  display: flex;
  justify-content: center;
}
.group-work {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  /* grid-template-rows: 1fr 1fr 1fr; */
}
.box {
  width: 15vw;
  height: 15vw;
  margin: 2vw;
  background: radial-gradient( rgb(93, 221, 144), rgb(35, 217, 245));
  border-radius: 20px;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 13px 27px -5px, rgba(0, 0, 0, 0.3) 0px 8px 16px -8px;
  cursor: pointer;
  transition: all 300ms ease;
}
.box:hover{
  box-shadow: none;
}

/* --------------------------------------------- */
 
 @media (max-width: 600px) {

main{
    padding: 6vw 0vw 20vw 0vw;
}
  .title {
  font-size: 8vw;
  font-weight: 600;
  margin: 2vw 0vw 5vw 0vw;
  

}

.title span {
  border-bottom: none;

}
.group-work {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
.box {
  width: 45vw;
  height: 45vw;
  margin: 2vw;
  background: radial-gradient( rgb(93, 221, 144), rgb(35, 217, 245));
  border-radius: 20px;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 13px 27px -5px, rgba(0, 0, 0, 0.3) 0px 8px 16px -8px;
}

 }
</style>
