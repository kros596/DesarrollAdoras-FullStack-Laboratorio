<h1>LABORATORIO - Desarrollo Full-Stack (Nivel 3) ED.2022</h1>
<p>
  En este laboratorio se solicitaba crear una aplicación haciendo uso de PHP y BBDD que permitiese el registro de nuevos usuarios, con las validaciones oportunas, y la consulta de los usuarios actualmente registrados.
</p>
<p>
 La presente entrega cuenta con dos elemenos, el archivo 'usuario.sql' referente a la BBDD y el archivo comprimido 'laboratorioSQL.zip', donde se encuentran los archivos de la aplicación:
  <ul>
    <li>formulario.html: Documento HTML con el contenido del formulario de inscripción.</li>
    <li>formulario.js: Documento JavaScript que ejecuta las funciones de validación de las entradas del usuario a nivel de cliente.</li>
    <li>style.css: Documento de Hoja de Estilos en Cascada que da estilo a los documentos HTML y a las entradas del usuario en función del resultado de la validación.</li>
    <li>subscribe.php: Documento PHP que contiene el código necesario para la conexión a la base de datos. Realiza las siguientes labores:
      <ul>
        <li>Recopila los datos del formulario</li>
        <li>Realiza una validación de las entradas de forma redundante a la parte de cliente.</li>
        <li>Intenta realizar la conexión a la BD.</li>
        <li>Si la conexión es satisfactoria, comprueba si ya se ha registrado el email solicitado, en caso afirmativo, cancela la inscripción</li>
        <li>Si no existe el email solicitado, registra al nuevo usuario en la tabla 'usuario' de la BD y muestra el contenido del archivo 'success.html'</li>
        <li>Si existen errores, muestra el error y habilita la opción de acceso al formulario de registro.</li>
      </ul>
    </li>
    <li>success.html: Documento HTML que se muestra dentro de subscribe.php cuando el registro es exitoso, y habilita la opción de consulta de los datos de los usuarios registrados.</li>
    <li>getUsers.php: Documento PHP que recopila los datos de los usuarios registrados en la aplicación (excepto la contraseña, por cuestiones de seguridad) y los muestra en formato de tabla.</li>
    <li>images: Directorio que contiene las imágenes (iconos) para la decoración gráfica resultante de la validación de las entradas.</li>
  </ul>
</p>
