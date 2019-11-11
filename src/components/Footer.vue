<template>
    <div class="box">
        <footer>
            <img src="../assets/logo2.svg"/>
            <div class="container">
            <div class="firts">

                <h2>Lorem ipsum dolor sit.</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio, dicta!</p>
            </div>
             <div class="firts">

                <h2>Lorem ipsum dolor sit.</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio, dicta!</p>
            </div>
             <div class="firts">

                <h2>Lorem ipsum dolor sit.</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio, dicta!</p>
            </div>
            </div>
            <div class="footer-logo">
                <div class="logo1">
                    <img src="../assets/icon-facebook.svg">
                </div>
                <div class="logo2">
                    <img src="../assets/icon-twitter.svg">
                </div>
                <div class="logo3">
                    <img src="../assets/icon-pinterest.svg">
                </div>
                <div class="logo4">
                    <img src="../assets/icon-instagram.svg">
                </div>

            </div>
            
            
        </footer>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins&display=swap');
.box {
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

footer {
    background:hsl(255, 11%, 22%);
    /* margin: 0% 10%; */
    
    

  
}

.container {
    padding-top: -20%;
}
img {
    display: block;
    margin: 0% auto;
    padding-top: 10%;
}

.firts {
    text-align: center;
    color: white;
    padding-bottom: 10%;
}



.firts h1 {
    font-weight: bold;
    padding: 0% 10%;
}

.firts p {
    color: rgb(202, 202, 202);
    padding: 0% 25%;
}
.footer-logo {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    padding: 0% 20%;
    grid-column-gap: 20px;
}

.logo4 {
    margin-bottom: 40%;
}

p {
    line-height: 25px;
}
</style>