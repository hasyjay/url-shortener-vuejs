<template>
  <div class="box">
   <div class="head">
     <div class="head-container">
     <img src="../assets/logo.svg">
     <div class="dash" @click="toggle = !toggle">

       <span></span>
       <span></span>
       <span></span>
     </div>
     </div>
     <ul class="navbar" :class="{menu: toggle}" >

       <li><a href="#">Features</a></li>
       <li><a href="#">Pricing</a></li>
       <li><a href="#">Resources</a></li>
       <li><a href="#">Login</a></li>
       <li><a href="#">Sign Up</a></li>
     </ul>
   </div>
   <section id="text-grid"> 
<img src="../assets/illustration-working.svg" width="338px">
<h1 class="text-head">More Than Just Shorter Links.</h1>
<p class="paragh">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Hic cupiditate debitis ullam dignissimos!</p>
<button class="btn"><a href="#">GET STARTED</a></button>


   </section>
  </div>
</template>

<script>
export default {
 data(){
   return{
     toggle: false
   }
 },
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

/* Mobile screen size */
@import url('https://fonts.googleapis.com/css?family=Poppins&display=swap');

.box {
  box-sizing: border-box;
}

*{
margin: 0;
padding: 0;

}
.head-container {
  position: relative;
  
}

.dash {
  position: absolute;
  left: 80%;
  bottom: 30%;
  
}
.dash> span {
  width: 30px;
  height: 5px;
  background: black;
  display: block;
  margin: 5px 0px;
  cursor: pointer;
  

}

.head ul li,a {
  padding: 10px 0px;
  list-style-type: none;
  text-transform: uppercase;
  text-align: center;
  margin-right: 15px;
  line-height: 6vh;
  color: white;
  text-decoration: none;
  cursor: pointer;
}

.head ul {
  background: hsl(257, 27%, 26%);
  border-radius: 10px;
  height: auto;
}
.navbar {
 display: none;
  transition: all 500ms linear;
}

.menu  {
 display: block;
 transition: all ease-in 500ms linear;
  
}

.head ul li:nth-child(3){
  border-bottom: 1px solid black;
  margin-right: 10px;
  margin-bottom: 5%;
}
.head ul li:nth-child(5){
  border: 1px solid hsl(180, 66%, 49%);
  border-radius: 20px;
  background: hsl(180, 66%, 49%);
  margin-left: 4%;
 
  /* background: green; */
}


img {
  padding: 20px;

}

#text-grid{
  display: grid;
  grid-template-rows: repeat(1, 1fr)

}

.btn {
  width: 50%;
   margin: 0px auto;
   border:  solid hsl(180, 66%, 49%);
   background: hsl(180, 66%, 49%);
   border-radius: 15px;
   text-align: center;
   margin-top: 4%;
}

.paragh,.text-head {
  text-align: center;
   padding: 0px 10px;
   margin: 5px 0px;
}

.text-head {
  font-size: 35px;
  
 
}

.paragh {
  font-size: 15px;
  color: rgba(172, 171, 171, 0.753);
}
</style>
