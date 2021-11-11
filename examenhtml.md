<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="examen.css">
    <title>Document</title>
</head>
<body>
    <h1><center>Hotel el casarito</center></h1>
    <br>
    <br>
    <div class="topnav">
      <a href="#">Inicio</a>
      <a href="#">Precios</a>
      <a href="#">Reserva</a>
    </div>
    <br>
    <p>El hotel casarito es un hotel situado en salamanca que en su zona nos podemos encontrar el camino del peñasco, la senda de los castaños centenarios y la ruta por la sierra de francia.</p>
    
    <div class="hover01 column">
        <div>
          <figure><img src="examen1.jpg" /></figure>
          <span>Camino del peñasco</span>
        </div>


        <div class="hover02 column">
            <div>
              <figure><img src="examen2.jpg" /></figure>
              <span>senda los castaños centenarios</span>
            </div>


        <div class="hover02 column">
            <div>
              <figure><img src="examen3.jpg" /></figure>
              <span>Ruta por la sierra de Francia</span>
            </div>
    <h1><center>Precios</center></h1>
    <br>
    <br>
    <br>
    <table>
      <tr>
        <th>Hotel</th>
        <th>Precio alto</th>
        <th>Precio bajo</th>
      </tr>
      <tr>
        <td>Las cavenes del cabaco</td>
        <td>50</td>
        <td>38</td>
      </tr>
      <tr>
        <td>La alberca</td>
        <td>40</td>
        <td>60</td>
      </tr>
      <tr>
        <td>Abadía de los templarios</td>
        <td>120</td>
        <td>105</td>
      </tr>
    </table>
    <br>
    <br>
    <h1><center>Reserva</center></h1>
    <from acttion="submeter-formulario.php" method="post">

        
      <p>
          <label for="nombre" class="colocar_nombre">Nombre
              <span class="obligatorio">*</span>
          </label>
            <input type="text" name="introducir_nombre" id="nombre" required="obligatorio" placeholder="Escribe tu nombre">
      </p>

      <p>
          <label for="Apellidos" class="colocar_Apellidos">Apellidos
              <span class="obligatorio">*</span>
          </label>
            <input type="text" name="introducir_Apellidos" id="Apellidos" required="obligatorio" placeholder="Escribe tus Apellidos">
      </p>

      <p>
          <label for="email" class="colocar_email">Email
              <span class="obligatorio">*</span>
          </label>
            <input type="email" name="introducir_email" id="email" required="obligatorio" placeholder="Escribe tu email">
      </p>

      <p>
          <label for="DNI" class="colocar_DNI">DNI
              <span class="obligatorio">*</span>
          </label>
            <input type="DNI" name="introducir_DNI" id="email" required="obligatorio" placeholder="Escribe tu DNI">
      </p>

      <p>
          <label for="telefono" class="colocar_telefono">Teléfono
          </label>
            <input type="tel" name="introducir_telefono" id="telefono" placeholder="Escribe tu telefono">
      </p>
      
      <form>
      <p>
          <label for="asunto" class="colocar_asunto">Asunto
          </label>
            <input type="text" name="introducir_asunto" id="asunto" required="obligatorio" placeholder="Escribe un asunto">
      </p>

      <button type="submit" name="enviar_formulario" id="enviar"><p>Enviar</p></button>

      <p class="aviso">
          <span class="obligatorio">*</span>los campos son obligatorios.
      </p>
  </from>
    </div>
</div>

    
</body>
</html>
