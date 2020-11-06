# mensajes App

Aplicación para evidenciar algunos de los fallos que se conocen en OWASP


## Estructura

index.php (inicio de la aplicación)
- validar si existe una sesión de usuario, si existe, redireccionar a panel.php
- si no existe una sesión, redireccionar a login.php
- en login.php vamos a incluir un enlace hacia registro.php
- login va a contener un formulario para iniciar sesión y un enlace a registro.php

## Arquitectura

- frontend: 
html (estructura)
css (diseño)
javascript (funcionalidad)

- backend:
servidor web (apache o nginx)
lenguaje backend php

- persistencia:
sgbd (mysql) 

## Métodos HTTP (forms y APIs)

- get (traer información)
- post (enviar y guardar información)
- put patch (para actualizar información)
- delete (eliminar información)
CRUD (create, read, update, delete)
