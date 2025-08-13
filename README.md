# Introduccion-a-los-lenguajes-de-internet
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- esto es un comentario -->
     <h1>Titulo principal</h1>
     <!-- <h2> titulo secundario</h2> -->
    
     <h2>Titulo secundario</h2>
     <h3>titulo tercero </h3>
     <h4> titulo cuarto </h4>
     <h5> titulo quinto </h5>
     <h6> titulo sexto </h6>
     <p> esto es un parrafo en un sitio web</p>
     <a href="https://chromewebstore.google.com/" target="_blank"> click aqui</a>
     <!-- <img src="https://cdn.pixabay.com/photo/2023/03/16/08/42/camping-7856198_640.jpg" alt="Atardecer "> -->
     
     
     <form action="/procesar-registro" method="post">
        <label for="genero">Genero</label>
        <label for="masculino">Masculino</label required>
        <input type="radio" name="genero" value="masculino">
        <label for="femenino">Femenino</label>
        <input type="radio" name="genero" value="femenino" required>
        <label for="otro">Otro</label>
        <input type="radio" name="genero" value="otro">

        <label for="pais">Pais</label>
        <select name="pais" id="pais" required>
            <option value="">Selecciona un pais</option>
            <option value="es">España</option>
            <option value="mx">Mexico</option>
            <option value="ar">Argentina</option>
            <option value="co">Colombia</option>
        </select>

        <label for="nombre">Nombre</label>
        <input type="text" name="nombre" id="nombre" required>
        <label for="edad">Edad</label>
        <input type="number" name="edad" id="edad" required>
        <label for="email">Email</label>
        <input type="email" name="email" id="email" placeholder="ejemplo@correo.com" required>
        <label for="password">Contraseña</label>
        <input type="password" name="password" id="password" placeholder="aZ-0-9*" required>

        <label for="intereses">Intereses</label >
        <label for="deportes">Deportes</label>
        <input type="checkbox" name="intereses[]" id="deportes" value="deportes" >
        <label for="musica">Musica</label>
        <input type="checkbox" name="intereses[]" id="musica" value="musica" >
        <label for="lectura">Lectura</label>
        <input type="checkbox" name="intereses[]" id="lectura" value="lectura" >


        <label for="terminos">
            <input type="checkbox" id="terminos" name="terminos" required>
            Acepto los terminos y condiciones
        </label>


        <button type="submit " value="registrarse" id="btnregistrarse">Registrarse</button>

     </form>



    
</body>
</html>
