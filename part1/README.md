# Part 1 (Color & Gray Scale image | Transformations)

 - Converting a color image to grayscale using OpenCV
 - Doing some transformations/changes with both the color & gray versions
 - Creating a Gaussian pyramid of the image and displaying it as a single image.
   What is the space requirement for the pyramid?
   What is the size of the smallest rectangular image needed to pack the pyramid.

   code: part1.py

Results
-------

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>

<center><h2>Problem 1: BGR and GRAYSCALE</h2></center>

<div class="row">
  <div class="column">
    <h2>original color image</h2>
    <img src="original.jpg" width="200">
  </div>
  <div class="column">
    <h2>GRAY SCALE image</h2>
    <img src="gray.jpeg" width="200">
  </div>
</div>

<center><h2>Problem 2: Transformations</h2></center>

<div class="row">
  <div class="column">
    <h2>Translation: Color image translated Right & Down</h2>
    <img src="translated_right_down.jpeg" width="200">
  </div>
  <div class="column">
    <h2>Rotation: Color image rotated 270 degree</h2>
    <img src="rotated_270.jpeg" width="200">
  </div>
</div>

<div class="row">
  <div class="column">
    <h2>Reflection: Gray scale image reflected vertically</h2>
    <img src="vertical_flipped.jpeg" width="200">
  </div>
  <div class="column">
    <h2>Color space change: BGR to HSV</h2>
    <img src="hsv.jpeg" width="200">
  </div>
</div>

<div class="row">
  <div class="column">
    <h2>Shearing: Gray scale image sheared horizontally</h2>
    <img src="horizontal_sheared.jpeg" width="200">
  </div>
  <div class="column">
    <h2>Blurring: Color image blurred</h2>
    <img src="blurred.jpeg" width="200">
  </div>
</div>

<div class="row">
  <div class="column">
    <h2>Resizing: Color image resized to double</h2>
    <img src="double_sized.jpeg" width="200">
  </div>
  <div class="column">
  </div>
</div>

<center><h2>Problem 3:  Gaussian pyramid</h2></center>

<div class="row">
  <div class="column">
    <h2> Gaussian pyramid</h2>
    <p>Dislay gaussian pyramid in a single image</p>
    <img src="pyramid.jpeg" width="200">
  </div>
  <div class="column">
  </div>
</div>


</body>
</html>
