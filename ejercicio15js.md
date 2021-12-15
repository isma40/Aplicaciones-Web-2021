<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 15</title>
    <script>
        function genera_tabla() {
           
        var body    = document.getElementsByTagName("body")[0];
        var tabla   = document.createElement("table");
        var tblBody = document.createElement("tbody");
            
        for (var x=0;x<2*3;x++) {
            var fila = document.createElement("tr");
            
            for (var z=0; z< 2*2; z++) {
            var celda = document.createElement("td");
            var textoCelda = document.createTextNode("Celda en la fila "+ x +", columna "+ z );
            
            celda.appendChild(textoCelda);
            fila.appendChild(celda);
            }
            tblBody.appendChild(fila);
        }
        tabla.appendChild(tblBody);
        body.appendChild(tabla);
        tabla.setAttribute("border", "3");
    }
    </script>
</head>
<body>
    <input type="button" value="Genera una tabla" onclick="genera_tabla()">
</body>
</html>
