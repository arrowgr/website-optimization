Website hosting
https://feedaki.gr/Pizza/index.html

Local

Open index.html in a browser

Check with:
PageSpeed Insights 
gtmetrix


Optomize Images with http://optimizilla.com/

index.html
add size on images
minify html with http://www.willpeavy.com/minifier/



pizza.html

minify html with http://www.willpeavy.com/minifier/

remove  
</html>
style="width:33.33%; height: 325px;"

add
<div id="pizza0" class="col-4 randomPizzaContainer">
<div id="pizza1" class="col-4 randomPizzaContainer">
<div class="lesswidth">
<div class="maxwidth">




style.css
add
.randomPizzaContainer



main.js

add
pizzaDescriptionContainer.className("max-width");
pizzaImageContainer.className("less-width");

edit 
var rows = Math.ceil(window.innerHeight /256) * 8;
function changePizzaSizes(size) {


document.addEventListener('DOMContentLoaded', function () {
var dose = (Math.floor(i / cols) * s) + 'px' ;
elem.style.transform= 'translateY('+dose+')';
change querySelector  with getElementById on movingPizzas1,pizzaSize

out of loop var top = (document.body.scrollTop / 1250);


remove
//pizzaContainer.style.width = "33.33%";
//	pizzaContainer.style.height = "325px";
// pizzaDescriptionContainer.style.width = "65%";
	//pizzaImageContainer.style.width = "35%";
	
 