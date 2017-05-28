[![Build Status](https://travis-ci.com/ULL-ESIT-DSI-1617/proyecto-dsi-berkan-javier-35l1-1.svg?token=zsg7W1SNzKPhkVpKaLTH&branch=master)](https://travis-ci.com/ULL-ESIT-DSI-1617/proyecto-dsi-berkan-javier-35l1-1)

# CASIANO'S ADVENTURES

Aplicación/Juego web desarrollado como proyecto final de la asignatura Desarrollo de Sistemas Informáticos. Para esto han sido usadas varias de las tecnologías vistas y explicadas a lo largo del curso.

La app consta de dos pantallas: una primera en la que los usuarios deben hacer login para acceder al juego pudiendo también registrarse o cambiar su contraseña; y una segunda en la que se puede iniciar una nueva partida, cerrar sesión o ver las mejores puntuaciones globales.

## Autores

[Berkan Reyes Hernández](https://berkanrhdz.github.io)

[Javier Antonio González Hernández](https://javiergonher.github.io/)

## Despliegue y Enlaces
[Enlace documentación - ghpages](https://ull-esit-dsi-1617.github.io/proyecto-dsi-berkan-javier-35l1-1/)

## Forma de uso local

## Tecnologías
Como se dijo anteriormente, para el desarrollo de la aplicación se han usado diversar tecnologías que serán explicadas a continuación y se dirá para que han sido utilizadas. 

### NPM 
Npm es el manejador de paquetes por defecto para Node.js, un entorno de ejecución para JavaScript.

La mejor manera de gestionar los paquetes instalados localmente NPM es crear un package.json y eso es lo que se ha hecho, un package.json con la información del paquete, las dependencias necesarias para la ejecución de la app y algunas tareas/scripts para ejecutar pruebas.

### NODEJS
Node es un intérprete Javascript del lado del servidor que cambia la noción de cómo debería trabajar un servidor. Su meta es permitir a un programador construir aplicaciones altamente escalables y escribir código que maneje decenas de miles de conexiones simultáneas en una sólo una máquina física.

Aquí ha sido utilizada de la manera explicada, siendo el método para decirle al servidor como debe operar tras un login, un registro, un cambio de contraseña, etc. Además gestiona la base de datos a través del middleware mongoose.

### MONGODB

### HTML - CSS - JAVASCRIPT

### MOCHA Y CHAI
Mocha es un framework de pruebas de JavaScript que se ejecuta en Node.js. Nos da la posibilidad de crear tanto tests síncronos como asíncronos de una forma muy sencilla. 

Chai es un librería de aserciones, la cual se puede emparejar con cualquier marco de pruebas de Javascript. Chai tiene varias interfaces: assert, expect y should, que permiten al desarrollador elegir el estilo que le resulte más legible y cómodo a la hora de desarrollar sus tests.

Esto ha sido utilizado para realizar pruebas sobre el código del juego. En el directorio /test se encuentran los archivos correspondientes.

### KARMA
Karma es esencialmente una herramienta que crea un servidor web para ejecutar las pruebas para cada navegador asociado. El resultado de cada test en cada navegador asociado es examinado y desplegado en la línea de comando del desarrollador para poder observar que test falla y que test se superan.

### TRAVIS
Travis permite conectar nuestro repositorio de Github y probar después de cada push que hagamos las pruebas mocha que hemos creado, regenerando el proyecto.

En nuestro caso ha sido creado el archivo .travis.yml configurado para ejecutar las pruebas con karma.

### JSDOC
JSDoc es una aplicación realizada en Perl que nos genera la documentación de nuestros scripts Javascript de forma automática. Basado en el conocido javadoc, obtiene los comentarios de documentación (/** .. */) para obtener la informacion sobre las funciones.

Esta tecnología ha sido utilizada para documentar las distintas clases que conforman el juego javascript desarrollado para la app web.

