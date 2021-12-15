<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 18</title>
    <script>
        
        var vocales = ["a", "e", "i", "o", "u"]
       
        function countVowel(str) {
        
        let contarVocal = 0;
        
            for (let letra of str.toLowerCase()) {
                if (vocales.includes(letra)) {
                    contarVocal++;
                }
            }
        
                return contarVocal
        }
        
        var palabra = prompt('Escribe una palabra: ');
        
        var resultado = countVowel(palabra);
        alert('La palabra tiene ' + resultado + ' vocales');
    </script>
</head>
<body>
    
</body>
</html>
