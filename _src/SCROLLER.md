# SLIDESHOW

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.mySlides {display:none;}
</style>
<body>

<div class="w3-content w3-display-container">

<div class="w3-display-container mySlides">
  <img src="/img/HerderVan.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-purple">
    Herder van
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/Landini.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-yellow">
    Landini
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/LucernePostRain.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-purple">
    Lucerne Land Post Rain
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/PerdelandPostRain.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-yellow">
    Horse Camp After Rain
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/RichardFlowers.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-purple">
    Richards Land Flowers After Rain
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/RichardsLandAfterRAin.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-yellow">
    Richards Land Growth After Rain
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/RichardsRainGrowth.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-purple">
    Richards Land Rain growth
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/RichardsWerf.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-yellow">
    Richards Land & Werfgebou
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/sannaskop1.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-purple">
    Sannaskop 1
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/sannaskop2.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-yellow">
    Sannaskop 2
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/sannaskop3.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-purple">
    Sannaskop 3
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/sannaskop5.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-yellow">
    Sannaskop 4
  </div>
</div>

<div class="w3-display-container mySlides">
  <img src="/img/sannaskop6.jpg" style="width:100%">
  <div class="w3-display-topleft w3-large w3-container w3-padding-16 w3-blue">
    Sannaskop 5
  </div>
</div>

<button class="w3-button w3-display-left w3-black" onclick="plusDivs(-1)">&#10094;</button>
<button class="w3-button w3-display-right w3-black" onclick="plusDivs(1)">&#10095;</button>

</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>