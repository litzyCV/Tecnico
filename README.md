<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Mi Aplicacion Movil</title>
<link rel="stylesheet" href="main.css">
</head>
<body>
<center>
<header><h1>Litzy</h1></header>
</center>
</body>
<main>
<div class="container">
<div class="shape-container"></div>
</div>
<canvas id="lienzo" width="400" height="400"></canvas>
<div id="paleta"></div>
</main>
<footer>
<p>&copy; LitzyC.V</p>
</footer>
<script src="js/main.js"></script>
<script src="js/animation.js"></script> </body>
  <style>
    }
@media(max-width: 991px){
    .tablet{
        display: none;
    }
    .movil{
        display: none;
    }
}

    
body
{
    background: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRd475TCM4s8HPKQYe2t9-1NdBJz2DBhiSm2g&usqp=CAU.jpg);
    background-repeat: no-repeat;
    background-size: 110vw 110vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
}
header
{
    width: 100%;
    height: 100%;
}
nav
{
    float: right;
    margin: 20px;  
}
nav ul li
{
    list-style: none;
    position: relative; 
    float: left; 
    margin: 15px; 
}
nav ul li a
{
font-weight: bold; 
font-family:monospace;
font-size: 15px;
}

h1
{
    color: rgba(255, 252, 252, 0.995);
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    text-align: center;
}
p
{
    color: rgba(130, 123, 173, 0.895);
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; 
    font-size: xx-large;
}
img
{
    float:left;
    width: 100px;
    height: 100px;
    padding: 10px;
    margin-top:0px;
    margin-left: 0px;
}
  </style>
</html>
