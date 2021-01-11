Tercer intento para automatizar APIS
basado en el tutorial: https://www.youtube.com/playlist?list=PL6tu16kXT9PpgqfMbMdzUzDenYgb0gbk0

Video01
=======





Video02
=======
Installing JSON Server for API Testing with Rest-Assured

- Para instalar Json Server vamos a la siguiente página: https://github.com/typicode/json-server
- ejecutamos el siguiente comando: npm install -g json-server
- Creamos en la carpeta del proyecto un archivo db.json que contenga data para probar 
{
  "posts": [
    { "id": 1, 
      "title": "json-server", 
      "author": "typicode" }
  ],
  "comments": [
    { "id": 1,  
      "body": "some comment",  
      "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}

- Para comprobar que hemnos instalado ejecutamos el comando: json-server (en CMD)
  Se debe obtener una lista de opciones y ejemplos.
- Para conectar nuestro archivo con el Browser ejecutamos el siguiente comando
  json-server .\db.json  --> archivo con nuestra trama json
  Se obtiene lo siguiente:  
  Resources
  http://localhost:3000/posts
  http://localhost:3000/comments
  http://localhost:3000/profile

-  Si vamos al Browser y buscamos: http://localhost:3000/posts
   [
     {
       "id": 1,
       "title": "json-server",
       "author": "typicode"
     }
   ]

- Si vamos a la raiz http://localhost:3000 obtenemos
  Resources
	/posts 1x
	/comments 1x
	/profile object
	To access and modify resources, you can use any HTTP method:

	GET POST PUT PATCH DELETE OPTIONS

	undefined
	Documentation
	README
  Estos son todas las urls disponibles al inicio de estos tutoriales.



Video01
=======



Video01
=======

