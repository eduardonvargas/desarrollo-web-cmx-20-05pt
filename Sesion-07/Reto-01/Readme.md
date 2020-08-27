`Backend Fundamentals` > `S07 - Mongoose` 
	
### Reto 1

Es momento de probar los nuevos endpoints de la API, así que ejecuta el servidor y realiza las siguientes tareas.

1. Crea una cuenta de adoptapet en el endpoint `POST [/v1/usuarios](http://localhost:3000/v1/usuarios)` guarda el token que te devuelve la petición.
2. Obtén la información de tu perfil en el endpoint `GET [/v1/usuarios](http://localhost:3000/v1/usuarios)` ahora será necesario que cambies los headers de autenticación y pongas el token con el prefijo 'Bearer'.

    Ejemplo: `Authorization: 'Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...'`

3. Modifica tu nombre de usuario.
4. Modifica tu password
5. Ahora pregúntate: ¿en qué caso necesitaríamos conocer información sobre otro usuario?
6. Si el usuario no tiene la propiedad `tipo` cuando es creado en una petición POST, ¿podemos hacer algo para asignarle un tipo?

![image](https://user-images.githubusercontent.com/13757596/87738478-21ddc480-c7a3-11ea-9c9b-cf88868563ec.png)
