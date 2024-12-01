##Moodle en docker

Debemos crear obligatoriamente una carpeta (moodledata) para los datos persistentes de moodle.
Con el docker compose (.yml) especificamos la imagen de moodle y mysql (contenedores) a descargar, también le damos los parámetros de la base de datos a emplear (he dejado la base de datos por defecto) y creamos un volumen.
