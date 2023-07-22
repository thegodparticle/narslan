---
title: 2023 Conference on Implantable Auditory Prostheses
date: 2023-07-21
author: Niyazi Arslan
institution: Arizona State University
image:
  caption: 'Memorable moment with my academic hero, Professor Shannon'
  placement: 2 
---  

The Auditory Implant Lab participated in #CIAP2023, where we had the honor of presenting four insightful posters and delivering one podium presentation. Grateful for the opportunity to contribute to the conference and share our research findings.

For more information about the conference, you can visit the [CIAP2023 website](http://www.ciaphome.org/programs.html).

Take a look at some highlights from the conference:

<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade" onclick="toggleSlideshow()">
    <div class="numbertext">1 / 4</div>
    <img src="./CIAP1.png" style="width:100%">
    <div class="text"></div>
  </div>

  <div class="mySlides fade onclick="toggleSlideshow()">
    <div class="numbertext">2 / 4</div>
    <img src="./CIAP2.png" style="width:100%">
    <div class="text"></div>
  </div>

  <div class="mySlides fade onclick="toggleSlideshow()"">
    <div class="numbertext">3 / 4</div>
    <img src="./CIAP3.png" style="width:100%">
    <div class="text"></div>
  </div>
  
  <div class="mySlides fade onclick="toggleSlideshow()"">
    <div class="numbertext">4 / 4</div>
    <img src="./CIAP4.png" style="width:100%">
    <div class="text"></div>
  </div> 
</div>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<style>
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

.mySlides {
  display: none;
  position: relative;
  width: 100%;
  height: 500px;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 1s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 4s;
  animation-name: fade;
  animation-duration: 4s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
</style>


<script>
  let slideIndex = 0;
  showSlides();

  function showSlides() {
    let i;
    let slides = document.getElementsByClassName("mySlides");
    let dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 4000); // Change image every 4 seconds
  }
</script>
