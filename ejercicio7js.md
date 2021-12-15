<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 7</title>
    <script>
        var cambio = function (numero) {
        if (numero == 'uno') {
            boton1();
        } else {
            boton2();
        }
    }
        var boton1=function(){
        document.getElementById('boton1').style.visibility = "hidden";
        document.getElementById('boton2').style.visibility = "visible";
    }

        var boton2=function(){
        document.getElementById('boton2').style.visibility = "hidden";
        document.getElementById('boton1').style.visibility = "visible";
    }
    </script>
</head>
<body>
    <button id='boton1' onclick="cambio('uno')">Visible</button>
    <button id='boton2' onclick="cambio('dos')">Invisible</button>
</body>
</html>
