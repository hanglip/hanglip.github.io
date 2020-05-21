# GALLERY
<!--
<script src="/js/md-gallery.js"></script>

- <img src="/img/LucernePostRain.jpg" alt="Old Lucerne Land after rain" style="width: 400px;"/>
- <img src="/img/PerdelandPostRain.jpg" alt="Horse camp after rain" style="width: 400px;"/>
- <img src="/img/PostRainSkuurGums.jpg" alt="Skuur and gum trees after rain" style="width: 400px;"/>
- <img src="/img/RichardFlowers.jpg" alt="Richards Lands flowers after rain" style="width: 400px;"/>
- <img src="/img/RichardsRainGrowth.jpg" alt="Richards lands rain growth" style="width: 400px;"/>
- <img src="/img/VegGardenPostRain.jpg" alt="Vegetable Garden after rain" style="width: 400px;"/>
- <img src="/img/WorkerVegPatch.jpg" alt="Worker vegetable garden" style="width: 400px;"/>
- <img src="/img/HerderVan.jpg" alt="Massey Ferguson and Herder Van" style="width: 400px;"/>
- <img src="/img/Landini.jpg" alt="Landini" style="width: 400px;"/>
- <img src="/img/LSDrainPad.jpg" alt="Livestock drain pad" style="width: 400px;"/>
- <img src="/img/sannaskop1.jpg" alt="sannaskop 1" style="width: 400px;"/>
- <img src="/img/sannaskop2.jpg" alt="sannaskop 2" style="width: 400px;"/>
- <img src="/img/sannaskop3.jpg" alt="sannaskop 3" style="width: 400px;"/>
- <img src="/img/sannaskop4.jpg" alt="sannaskop 4" style="width: 400px;"/>
- <img src="/img/sannaskop5.jpg" alt="sannaskop 5" style="width: 400px;"/>
- <img src="/img/sannaskop6.jpg" alt="sannaskop 6" style="width: 400px;"/>

<script>
	md_gallery({
		'list_type':'ul',
		'class_name':'gallery',
		'tag_type':'article'
	});
</script>

-->

<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.mySlides {display:none;}
</style>

<div class="w3-content w3-display-container">
  <img class="mySlides" src="/img/LucernePostRain.jpg" alt="Old Lucerne Land after rain" style="width: 100%">
  <img class="mySlides" src="/img/PerdelandPostRain.jpg" alt="Horse camp after rain" style="width: 100%">
  <img class="mySlides" src="/img/PostRainSkuurGums.jpg" alt="Skuur and gum trees after rain" style="width: 100%">
  <img class="mySlides" src="/img/RichardFlowers.jpg" alt="Richards Lands flowers after rain" style="width: 100%">

  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
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


