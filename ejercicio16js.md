<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 16</title>
    <script>
        var numero1 = parseInt(prompt(alert('1. Escriba el primero numero: ')))
        var numero2 = parseInt(prompt(alert('2. Escriba el segundo numero: ')))
        var numero3 = parseInt(prompt(alert('3. Escriba el tercer numero: ')))

        numero1 = parseInt(numero1);
        numero2 = parseInt(numero2);
        numero3 = parseInt(numero3);
        if (numero1 > numero2 && numero1 > numero3) {
            alert('El número ' + numero1 + ' es el mayor de los 3')
        } else if (numero2 > numero1 && numero2 > numero3) {
            alert('El número ' + numero2 + ' es el mayor de los 3')
        } else if (numero3 > numero2 && numero3 > numero1) {
            alert('El número tres ' + numero3 + ' es el mayor de los 3')
        }
    </script>
</head>
<body>
    
</body>
</html>
