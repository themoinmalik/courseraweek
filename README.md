<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Assignment solution for Module 2</title>
    <link rel="stylesheet" href="css/style.css">
    </head>

<body>
<header>
    <h1>Our Menu</h1>
</header>

<!-- 
A] Three are 3 containers i have created
1. the row class: with width 100%
2. the col class : for media queries...the responsive layout container for resizing as per the screen size [no padding margins here only percents] 
3. the contr class : here the section container (gray background) is placed and all the padding/margins are made to make them look apart
	this is the class that contains the <p> and the heading <h2>
B] Negative margins and relative postioning used for h2-->

<div class="row">
  <div class="col-lg-4 col-md-6 col-sm-11">
  <div class="contnr">
  <h2 class='chicken'>Chicken</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  </div>
  </div>

  <div class="col-lg-4 col-md-6 col-sm-11">
  <div class="contnr">
  <h2 class = "beef">Beef</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  </div>
  </div>

  <div class="col-lg-4 col-md-12 col-sm-11">
  <div class="contnr">
  <h2 class="sushi">Sushi</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  </div>
  </div>
</div>
</body>
