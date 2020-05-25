 
# SLIDES

<img class="mySlides" src="/img/LucernePostRain.jpg" alt="Old Lucerne Land after rain" style="width: 100%"/>
<img class="mySlides" src="/img/PerdelandPostRain.jpg" alt="Horse camp after rain" style="width: 100%"/>
<img class="mySlides" src="/img/PostRainSkuurGums.jpg" alt="Skuur and gum trees after rain" style="width: 100%"/>
<img class="mySlides" src="/img/RichardFlowers.jpg" alt="Richards Lands flowers after rain" style="width: 100%"/>
<img class="mySlides" src="/img/RichardsRainGrowth.jpg" alt="Richards lands rain growth" style="width: 100%"/>
<img class="mySlides" src="/img/VegGardenPostRain.jpg" alt="Vegetable Garden after rain" style="width: 100%"/>
<img class="mySlides" src="/img/WorkerVegPatch.jpg" alt="Allotment vegetable garden" style="width: 100%"/>
<img class="mySlides" src="/img/HerderVan.jpg" alt="Massey Ferguson and Herder Van" style="width: 100%"/>
<img class="mySlides" src="/img/Landini.jpg" alt="Landini" style="width: 100%"/>
<img class="mySlides" src="/img/LSDrainPad.jpg" alt="Livestock drain pad" style="width: 100%"/>
<img class="mySlides" src="/img/sannaskop1.jpg" alt="Sannaskop 1" style="width: 100%"/>
<img class="mySlides" src="/img/sannaskop2.jpg" alt="Sannaskop 2" style="width: 100%"/>
<img class="mySlides" src="/img/sannaskop3.jpg" alt="Sannaskop 3" style="width: 100%"/>
<img class="mySlides" src="/img/sannaskop4.jpg" alt="Sannaskop 4" style="width: 100%"/>
<img class="mySlides" src="/img/sannaskop6.jpg" alt="Sannaskop 6" style="width: 100%"/>

<button class="w3-button w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
<button class="w3-button w3-display-right" onclick="plusDivs(+1)">&#10095;</button>

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
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  x[slideIndex-1].style.display = "block";
}

</script>