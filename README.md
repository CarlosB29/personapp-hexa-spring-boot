Antes de clonar el siguiente repositorio debe tener en cuenta los siguientes aspectos.
- MariaDB en el puerto 3307.
- MongoDB en el puerto 27017.

Primer paso para poder configurar la configuración realizada por el equipo 7

1. Debes tener instlado en tu computador Maven para poder correr un código de Maven 
2. Ejecuta el siguiente comando en PowerShell para construir el proyecto usando Maven:mvn clean install.

Ahora dentro de el código en el IDE que estas corriendo ejecuta el siguiente código:

1. Ejecutar el adaptador REST: java -jar .\rest-input-adapter\target\rest-input-adapter-0.0.1-SNAPSHOT.jar.
2. Ejecutar el adaptador CLI: java -jar .\cli-input-adapter\target\cli-input-adapter-0.0.1-SNAPSHOT.jar.

El adaptador REST se encuentra disponible en el puerto 3000. Para verificar las peticiones que esta realizando al buscador entre a la siguiente URL EN DONDE ENCONTRARA EL Swagger.
1. http://localhost:3000/swagger-ui.html