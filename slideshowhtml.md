<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="slideshow.css">

    <title>Document</title>
</head>
<body>
    <script src="slideshow.js"></script>
    <div class="slideshow-container">

        <div class="mySlides fade">
          <div class="numbertext">1 / 9</div>
          <img src="jugador.jpg" style="width:100%">
          <div class="text">Juan Fuentes</div>
        </div>
        
        <div class="mySlides fade">
          <div class="numbertext">2 / 9</div>
          <img src="jugador2.jpg" style="width:100%">
          <div class="text">Samuel Pariente</div>
        </div>
        
        <div class="mySlides fade">
          <div class="numbertext">3 / 9</div>
          <img src="jugador3.jpg" style="width:100%">
          <div class="text">Sindy Ramos</div>
        </div>

        <div class="mySlides fade">
          <div class="numbertext">4 / 9</div>
          <img src="jugador6.jpg" style="width:100%">
          <div class="text">lucia Soria</div>
        </div>

        <div class="mySlides fade">
          <div class="numbertext">5 / 9</div>
          <img src="jugador7.jpg" style="width:100%">
          <div class="text">Carlos Medina</div>
        </div>

        <div class="mySlides fade">
          <div class="numbertext">6 / 9</div>
          <img src="jugador11.jpg" style="width:100%">
          <div class="text">Ismael Peralta</div>
        </div>


        <div class="mySlides fade">
          <div class="numbertext">8 / 9</div>
          <img src="jugador8.jfif" style="width:100%">
          <div class="text">Yeray</div>
        </div>

        <div class="mySlides fade">
          <div class="numbertext">9 / 9</div>
          <img src="jugador10.jpg" style="width:100%">
          <div class="text">Jordan</div>
        </div>
        
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
        
        </div>
        <br>
        
        <div style="text-align:center">
          <span class="dot" onclick="currentSlide(1)"></span> 
          <span class="dot" onclick="currentSlide(2)"></span> 
          <span class="dot" onclick="currentSlide(3)"></span> 
        </div>
</body>
</html>

