---
title: 2023 Conference on Implantable Auditory Prostheses
date: 2023-07-21
author: Niyazi Arslan
institution: Arizona State University
image:
  caption: 'Memorable moment with my academic hero, Professor Shannon'
  width: 50px
  height: 300px
  placement: 2 
---  

The Auditory Implant Lab participated in #CIAP2023, where we had the honor of presenting four insightful posters and delivering one podium presentation. Grateful for the opportunity to contribute to the conference and share our research findings.

For more information about the conference, you can visit the [CIAP2023 website](http://www.ciaphome.org/programs.html).


<!-- Add your slideshow here -->
<div class="slideshow-container">
  <div class="slide">
    <img src="./CIAP1.png" alt="Slide 1">
  </div>
  <div class="slide">
    <img src="./CIAP2.png" alt="Slide 2">
  </div>
  <div class="slide">
    <img src="./CIAP3.png" alt="Slide 3">
  </div>
  <div class="slide">
    <img src="./CIAP4.png" alt="Slide 4">
  </div>  
</div>

<div class="navigation">
  <a class="prev" onclick="changeSlide(-1)">&#10094;</a>
  <a class="next" onclick="changeSlide(1)">&#10095;</a>
</div>

<style>
  /* Add CSS styles for the slideshow here */
  .slideshow-container {
    position: relative;
    width: 100%;
  }

  .slide {
    display: none;
  }

  .slide img {
    width: 100%;
    height: auto;
  }

  /* CSS styles for the navigation arrows */
  .navigation {
    text-align: center;
    margin-top: 10px;
  }

  .navigation a {
    font-size: 36px; /* Adjust the arrow size as per your preference */
    cursor: pointer;
    text-decoration: none;
  }
</style>

<script>
  let slideIndex = 1;
  showSlide(slideIndex);

  function changeSlide(n) {
    showSlide(slideIndex += n);
  }

  function showSlide(n) {
    const slides = document.getElementsByClassName("slide");
    if (n > slides.length) {
      slideIndex = 1;
    }
    if (n < 1) {
      slideIndex = slides.length;
    }
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slides[slideIndex - 1].style.display = "block";
  }
</script>