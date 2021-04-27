# Test-Fullstack

Ejercicio de evaluación

El objetivo del ejercicio es crear un conjunto de aplicaciones (un front y un back con conexion a base de datos) para administrar "Mi musica".

Requerimientos

Backend:

* Puede utilizar la tecnologia/framework/lenguaje que desee, puntos extra por usar Groovy/Grails.
* Debe conectarse a una base de datos para almacenar la información (puede utilizar el motor de base de datos que desee)
* Cada modelo debe tener su controlador CRUD, debe responder a sus correspondientes GET, GET(id), POST, PUT, DELETE.

Frontend:

* Utilizar ReactJs desde Visual Studio Code como IDE
* Cada modelo debe tener su vista de listado con funciones o accesos para agregar nuevo, editar y eliminar
* Cada modelo debe tener su vista de formulario de datos donde se registra y/o edita información
* La aplicación debera tener una vista inicial con un menu para navegar a las otras vistas.
* Cada modelo debe tener un servicio para consumir sus correspondientes CRUD de el Back.

Historias de usuario:

* El usuario debera tener la facultad de enlistar, dar de alta, editar y eliminar albumes y canciones.
* El usuario debera tener la facultad de enlistar sus playlist.
* El usuario debera tener la facultad de agregar y remover canciones de la playlist que desee.

Modelos:
Album
- Id [Int]
- Nombre [String]
- Artista [String]
- Status [Boolean]
Cancion
- Id [Int]
- Nombre [String]
- Duración [String]
- Status [Boolean]
Playlist
- Id [Int]
- Nombre [String]


Nota: Tomese solo como manejo de datos, no se va a almacenar ningun archivo de audio.

Nota: Debe subir las pruebas a la plataforma que desees; puedes usar Bitbucket, Gitlab, Github o cualquier plataforma de control de versiones. Debe de estar público y que nosotros tengamos acceso para poder evaluarlas.
