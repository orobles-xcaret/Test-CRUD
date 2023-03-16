El objetivo es crear una aplicación que maneje la lógica para permitir que el usuario inicie sesión y vea la vista principal cada vez que inicie la aplicación.

Requerimientos:
Generar una pantalla para autenticarse con correo electrónico y contraseña (puede usar datos estáticos para validar lo que el usuario escribe en el formulario)
La sesión del usuario deberá almacenarse localmente.
El usuario deberá poder cerrar sesión.
Consumir Pokemon API Docs. https://pokeapi.co/docs/v2 como fuente de información, tomar en cuenta que tiene un límite de peticiones.
Al iniciar sesión dirigir al usuario a la vista de listado de pokemons.
Al hacer click sobre algun registro del listado redirigir a la vista de detalle del pokemon, ya sea en una ventana emergente, modal o otra vista adicional.
Subir el codigo a Github este debe ser publico para poder bajarlo y ejecutarlo.

Puntos extra:
Generar una API middleware para triangular las solicitudes del front y la PokeAPI
El objetivo de esta API middleware sera guardar un log en un archivo de texto de las solicitudes y respuesas entre el front y la PokeAPI
