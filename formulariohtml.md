<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="formulario2.css">
    
</head>
<body>
    <div class="contact_form">
      <div class="formulario">
          <h1>Formulario</h1>
          <h3>completa los datos</h3>
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
            <label for="email" class="colocar_email">email
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
            <label for="telefono" class="colocar_telefono">telefono
            </label>
              <input type="tel" name="introducir_telefono" id="telefono" placeholder="Escribe tu telefono">
        </p>
        
        <form>
        <p>
            <label for="asunto" class="colocar_asunto">asunto
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
