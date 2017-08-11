<!DOCTYPE html>
<html>
<head>
<title>Get It Out Diaries</title>

    
    
<link href='https://fonts.googleapis.com/css?family=Fredoka One' rel='stylesheet'>
<style>
body {
    font-family: 'Fredoka One';font-size: 22px;
}
</style>

<body style="background-color:lightgray;">
    
    
    <script type="text/javascript" src="//code.jquery.com/jquery-1.10.2.min.js"></script>
    <script type="text/javascript" src="https://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/alphabet.js"></script>
  </head>
  
    <title>W3.CSS</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>

<!-- Sidebar -->
<div class="w3-sidebar w3-bar-block" style="display:none" id="mySidebar">
  <button onclick="w3_close()" class="w3-bar-item w3-button w3-large">Close &times;</button>
  <a href="https://zeita101.github.io/portfolio/get_it_out_home.html" class="w3-bar-item w3-button">Home</a>
  <a href="https://zeita101.github.io/portfolio/get_it_out_aboutthecreators.html" class="w3-bar-item w3-button">About The Creators</a>
  <a href="https://zeita101.github.io/portfolio/get_it_out_prompts2.html" class="w3-bar-item w3-button">Prompts</a>
  <a href="https://zeita101.github.io/portfolio/get_it_out_freethoughts.html" class="w3-bar-item w3-button">Free Thoughts</a>
  <a href="https://zeita101.github.io/portfolio/get_it_out_encouragement.html#" class="w3-bar-item w3-button">Encouragement</a>
  <a href="https://zeita101.github.io/portfolio/get_it_out_contactus.html" class="w3-bar-item w3-button">Contact Us</a>
  <a href="https://zeita101.github.io/portfolio/get_it_out_reflection.html" class="w3-bar-item w3-button">Reflection</a>
</div>

<!-- Page Content -->
<div class="w3-gray">
  <button class="w3-button w3-gray w3-xlarge" onclick="w3_open()">☰</button>
  <div class="w3-container">
    <h1><font color="#DC3A3A"> <center></h1>
  </div>
</div>


<div class="w3-container">

</div>

<script>
function w3_open() {
    document.getElementById("mySidebar").style.width = "100%";
    document.getElementById("mySidebar").style.display = "block";
}
function w3_close() {
    document.getElementById("mySidebar").style.display = "none";
}
</script>

      
      
  
  <body>
    <canvas id="myCanvas"></canvas>
    <script type="text/javascript" src="https://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/bubbles.js"></script>
    <script type="text/javascript" src="main.js"></script>

   
      
      
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing:border-box}
body {font-family: Verdana,sans-serif;}
.mySlides {display:none}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* The dots/bullets/indicators */
.dot {
  height: 13px;
  width: 13px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 100px) {
  .text {font-size: 11px}
}
</style>
<body>


<center>
<div class="mySlides fade">
  <div class="numbertext">1 / 23</div>
  <img src="2.png" style="width:50%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 23</div>
  <img src="3.png" style="width:50%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 23</div>
  <img src="4.png" style="width:50%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 23</div>
  <img src="5.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">5 / 23</div>
  <img src="6.png" style="width:50%">
  <div class="text"></div>
</div>
    
 <div class="mySlides fade">
  <div class="numbertext">6 / 23</div>
  <img src="7.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">7 / 23</div>
  <img src="8.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">8 / 23</div>
  <img src="9.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">9 / 23</div>
  <img src="10.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">10 / 23</div>
  <img src="11.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">11 / 23</div>
  <img src="12.png" style="width:50%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">12 / 23</div>
  <img src="13.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext"13 / 23</div>
  <img src="14.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">14 / 23</div>
  <img src="15.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">15 / 23</div>
  <img src="16.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">16 / 23</div>
  <img src="17.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">17 / 23</div>
  <img src="18.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">18 / 23</div>
  <img src="19.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">19 / 23</div>
  <img src="20.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">20 / 23</div>
  <img src="21.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">21 / 23</div>
  <img src="22.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">22 / 23</div>
  <img src="23.png" style="width:50%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">22 / 23</div>
  <img src="24.png" style="width:50%">
  <div class="text"></div>
</div>

</div>
    </center>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
       slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex> slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 1000); // Change image every 3 seconds
}
</script>


<img src="2.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="3.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="4.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="5.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="6.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="7.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="8.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="9.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="10.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="11.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="12.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="13.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="14.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="15.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="16.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="17.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="18.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="19.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="20.png" alt="Mountain View" style="width:500px;height:500px;"> 
<img src="21.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="GET it out! 2.png" alt="Mountain View" style="width:500px;height:500px;">

      
<img src="25.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="26.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="27.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="28.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="29.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="30.png" alt="Mountain View" style="width:500px;height:500px;">

<img src="31.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="32.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="33.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="34.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="35.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="36.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="37.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="38.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="39.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="40.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="41.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="42.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="43.png" alt="Mountain View" style="width:500px;height:500px;"> 
<img src="44.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="45.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="46.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="47.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="48.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="49.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="50.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="51.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="52.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="53.png" alt="Mountain View" style="width:500px;height:500px;"> 
<img src="54.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="55.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="56.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="57.png" alt="Mountain View" style="width:500px;height:500px;">
<img src="58.png" alt="Mountain View" style="width:500px;height:500px;">
</body>
   
      
</body>
</html>
