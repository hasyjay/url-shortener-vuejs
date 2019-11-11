<template>
    <div class="box">
        <section>
            <div class="input">
                    <input type="text" id="form"/>
            </div>
            <div class="bntn">
                     <button>SHORTEN IT</button>  
            </div>
           

        </section>

        <div id="url-render">

        </div>

        <div class="grid-row">
            <div class="letter">
                <h2>Advanced Statistics</h2>
                <p>Track how your links are performing across the web with our Advanced Statistics dashboard.</p>
            </div>
            <div class="grid-icon2">
                <img src="../assets/icon-brand-recognition.svg"/>
                  <h2>Brand Recognition</h2>
                  <p>Boost Your Brand Recognition With Each Click. generic links dont mean a thing. branded links help instill confidence in your contents  </p>
            </div>
            <div class="grid-icon3">
                <img src="../assets/icon-detailed-records.svg"/>
                  <h2>Detailed Records</h2>
                  <p>gain insight into who is clicking your links. knowing when and where people engage with your content helps inform better decision</p>
            </div>
            <div class="grid-icon4">
                <img src="../assets/icon-fully-customizable.svg"/>
                  <h2>Fully Customizable</h2>
                  <p>improve brand awareness and content discoverability through customizable links. supercharging audience engagements </p>
            </div>
          
        </div>
          <div class="lst-bg">
                <h1 class="heading-last">Boost Your Links Today.</h1>
                <div class="buttton">
                <button class="last-btn">Get Started</button>
                </div>

            </div>

      
           
      
    </div>
</template>

<script>
export default {
    
}
</script>


<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins&display=swap');

.box {
    font-family: 'Poppins', sans-serif;
}

section {
    grid-template-rows: 1fr ;
    grid-row-gap: 2rem;
    background: hsl(257, 27%, 26%);
    margin: 10% 10%;
    padding-top: 2%;
    padding-bottom: 2%;
    width: auto;
    
  
}

input {
    padding:10px 20px;
    border-radius: 10px;
    display: block;
    margin: 0px auto;
   
}

button {
   
    border: solid hsl(257, 27%, 26%);
    border-radius: 10px;
    color: white;
    background: hsl(180, 66%, 49%);
    margin: 0px auto;
    display: block;
    padding: 10px 78px;
}
.grid-row{
    /* background: hsl(0, 0%, 75%); */
    background-origin: padding-box;
    margin: 30px  10%;
    padding-bottom: 20%;
    height: auto;
    
}
.letter {
    
    padding-bottom: 3%;
    padding-top: 0%;
}


.letter h2  {
    text-align: center;
}

.letter p {
    text-align: center;
    padding: 0% 10%;
}
.grid-icon2 {
    background: white;
    margin-left: 20%;
    margin-right: 20%;
    padding-bottom: 3%;
    padding-top: 0%;
    margin-bottom: 17%;
    border-radius: 7px;
    box-shadow: 5px 5px 10px rgb(223, 218, 218);
    }

.grid-icon2 img   {
    display: block;
    margin: 0px auto;
     background: hsl(257, 27%, 26%);
    border-radius: 20px;
}

.grid-icon2 h2  {
    text-align: center;
}

.grid-icon2 p {
    text-align: center;
    padding: 0% 10%;

}

/* second row */

.grid-icon3 {
    background: white;
    padding-bottom: 3%;
    padding-top: 0%;
    margin-left: 20%;
    margin-right: 20%;
    margin-bottom: 17%;
    border-radius: 7px;
    box-shadow: 5px 5px 10px rgb(223, 218, 218);
}

.grid-icon3 img   {
    display: block;
    margin: 0px auto;
     background: hsl(257, 27%, 26%);
    border-radius: 20px;
}

.grid-icon3 h2  {
    text-align: center;
}

.grid-icon3 p {
    text-align: center;
    padding: 0% 10%;
}
/* 3rd row */

.grid-icon4 {
     background: white;
    padding-bottom: 3%;
    padding-top: 0%;
    margin-left: 20%;
    margin-right: 20%;
    margin-bottom: 17%;
    border-radius: 7px;
    box-shadow: 5px 5px 10px rgb(223, 218, 218);
}

.grid-icon4 img   {
    display: block;
    margin: 0px auto;
    background: hsl(257, 27%, 26%);
    border-radius: 20px;
}

.grid-icon4 h2  {
    text-align: center;
}

.grid-icon4 p {
    text-align: center;
    padding: 0% 10%;
}

.lst-bg {
    background: hsl(257, 27%, 26%);
    
   
}
p {
    text-transform: capitalize;
    color: gray;
}

.heading-last {
    color: white;
    padding: 0% 1%;
    text-align: center;
    padding-top: 10%; 
    font-size: 35px;
}
.buttton {
    padding-bottom: 10%;
}

.last-btn {
    color: white;
    
}
</style>