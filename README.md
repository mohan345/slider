<!DOCTYPE html>
<html>
<title>its_me</title>
<meta name="viewport"
content="width=device-width, initial-scale=1">
<link rel="stylesheet"
href = "file:///home/mohan/slider.htm">
<body>


<div class="w3-container">
 

<div class="w3-content w3-display-container">

<div class="w3-display-container mySlides">

     <img src="/home/mohan/Pictures/vir.png" style="width:50%">
     <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black"> highway
     </div>
</div>

<div class="w3-display-container mySlides">
     
     <img src="/home/mohan/Pictures/vir1.png" style="width:50%">
     <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black"> coldway
     </div>
</div>


</div>

<script>
var slideIndex = 0;
carousel();

function carousel() {
   
   var i;
   var x = document.getElementsByClassName("mySlides");
   for (i = 0; i < x.length; i++) {
      x[i].style.display = "none";
   }
   slideIndex++;
   if (slideIndex > x.length) {slideIndex = 1}
   x[slideIndex-1].style.display = "block";
   setTimeout(carousel, 2500); 
}
</script>


</body>
</html>
