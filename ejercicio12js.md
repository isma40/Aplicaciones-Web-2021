<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 12</title>
    <script>
        var numero = parseInt(prompt('Introduce un número: '));
        var resultado = parImpar(numero);
            alert('El numero ' + numero + ' es ' + resultado)
        function parImpar(numero) {
        if (numero % 2 == 0) {
            return "par";
        } else {
            return "impar";
        }
    }
    </script>
</head>
<body>
    
</body>
</html>
