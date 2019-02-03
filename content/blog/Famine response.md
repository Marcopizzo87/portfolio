---
title: "Famine Response"
date: 2017-5-10T11:40:14+02:00
publishdate: 2017-10-10T11:40:14+02:00
imagethumb: "/images/work_progress.png"
image: ""
description: "List of all information products published with REACH Initiative"
---
<div class='container'>
<h1>This is another post</h1>


<h2>Image Modal</h2>
<p>In this example, we use CSS to create a modal (dialog box) that is hidden by default.</p>
<p>We use JavaScript to trigger the modal and to display the current image inside the modal when it is clicked on. Also note that we use the value from the image's "alt" attribute as an image caption text inside the modal.</p>


<div class="row2">
  <div class="column2">
    <img src="/images/fsl_resp/foto1.jpg" style="width:100%" onclick="openModal();currentSlide(1)" class="hover-shadow cursor">
  </div>
  <div class="column2">
    <img src="/images/fsl_resp/foto2.jpg" style="width:100%" onclick="openModal();currentSlide(2)" class="hover-shadow cursor">
  </div>
  <div class="column2">
    <img src="/images/fsl_resp/foto3.jpg" style="width:100%" onclick="openModal();currentSlide(3)" class="hover-shadow cursor">
  </div>
  <div class="column2">
    <img src="/images/fsl_resp/foto4.jpg" style="width:100%" onclick="openModal();currentSlide(4)" class="hover-shadow cursor">
  </div>
</div>

<div id="myModal" class="modal">
    <span class="close cursor" onclick="closeModal()">&times;</span>
<div class="modal-content">

<div class="mySlides">
  <div class="numbertext"></div>
  <img class="demo" src="/images/fsl_resp/foto1.jpg" style="width:100%" alt="Nature and sunrise0">
</div>

<div class="mySlides">
  <div class="numbertext"></div>
  <img class="demo" src="/images/fsl_resp/foto2.jpg" style="width:100%" alt="Nature and sunrise1">
</div>

<div class="mySlides">
  <div class="numbertext"></div>
  <img class="demo" src="/images/fsl_resp/foto3.jpg" style="width:100%" alt="Nature and sunrise3">
</div>

<div class="mySlides">
  <div class="numbertext"></div>
  <img class="demo" src="/images/fsl_resp/foto4.jpg" style="width:100%" alt="Nature and sunrise4">
</div>
<a class="prev2" onclick="plusSlides(-1)">&#10094;</a>
<a class="next2" onclick="plusSlides(1)">&#10095;</a>
<div class="caption-container">
  <p id="caption"></p>
</div>
  <div class="dotbg" style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span> 
    <span class="dot" onclick="currentSlide(2)"></span> 
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
  </div>
</div>
</div>
</div>