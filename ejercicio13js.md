<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 13</title>
    <script>
        var letras = ['T', 'R', 'W', 'A', 'G', 'M', 'Y', 'F', 'P', 'D', 'X', 'B', 'N', 'J', 'Z', 'S', 'Q', 'V', 'H', 'L', 'C', 'K', 'E', 'T'];
        var numero = prompt("Introduce tu número de DNI (sin la letra)");
        
        if(numero < 0 || numero > 99999999) {
        alert("El número proporcionado no es válido");
        }
        else {
            var letraCalculada = letras[numero % 23];
            alert(letraCalculada);
        }

    </script>
</head>
<body>
</body>
</html>
