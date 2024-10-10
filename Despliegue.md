10\. una vez se haya creado la instancia "Web App", nos vamos al recurso y buscamos las configuraciones/settings, vamos a configuración y en la pestaña "Configuración general", buscamos la opción "HTTP version", la establecemos en dos.

11\. A continuación, nos vamos al apartado  "Development tools", le damos en "Go/Ir".

12\. En la parte superior del el desplegable "Debug console" escogemos la opción "CMD".

13\. En la nueva ventana en la cual nos encontramos, iremos a la carpeta "site" y después a la "wwwroot"

14\. Después de correr el comando  "npm run built" dentro de la nueva carpeta creada "dist" vamos a generar un archivo llamado "web.config". En este archivo estableceremos la configuración de los distintos headers de seguridad que queremos que nuestra app tenga.

15\. En la carpeta "wwwroot" subiremos un comprimido en el cual estarán los archivos que el comando "npm run built" guarda en la carpeta "dist" y el archivo que creamos en el paso anterior.
