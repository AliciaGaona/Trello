# Trello
Weekly Mission 4

## Explorando API REST Trello

Pasos:

1. Abri una cuenta de Trello https://trello.com/, confirmar correo, crear una contraseña y tener abierta la sesión.

2. Para jugar con el API Rest de Trello necesitamos un api key y un token que puedes solicitar aquí: https://trello.com/app-key, aqui meda mi token y mi key API para podre hacer uso de la API.


3. Visitar la documentación del Api Rest de Trello https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-group-boards, especificamnete se solicito revisar:

- Busca cómo crear un nuevo board.
- Busca cómo obtener la información de un board a partir de su ID
- Busca cómo obtener la lista de cards de un board
- Busca cómo crear una nueva card en un board

Se nos proporcionó una coleccion de postman con métodos.

![image](https://user-images.githubusercontent.com/99162884/167474766-5496d23d-8e32-43d9-b6fc-10cc6f94c352.png)


4. Importar colección a Postman

5. Listo ya puedes probar y jugar con la API de trello, en su documentación puedes encontrar todo lo que puedes hacer.

---

Resultado de probar la colección:


## Busca cómo crear un nuevo board.

Request POST:

![image](https://user-images.githubusercontent.com/99162884/167478345-0f4916b9-7d04-4818-8885-2e3913bbb9c5.png)

Mandas un post con la información que necesitas para crear un nuevo tablero.

Info: TOKEN, KEY API, NOMBRE

Petición:

![image](https://user-images.githubusercontent.com/99162884/167475869-8ebd5660-56f7-456a-892f-7878327c7bd9.png)


Respuesta API Trello:

![image](https://user-images.githubusercontent.com/99162884/167475529-71f345ee-e44c-4c13-a48e-57a6cde12439.png)

En acción:

![image](https://user-images.githubusercontent.com/99162884/167475441-010224e6-4f24-4ae0-9cf7-bad31072567c.png)

Guardamos el id del nuevo tablero, que viene en el response de la petición en postman.

![image](https://user-images.githubusercontent.com/99162884/167475723-da2153c1-c206-4f9e-9482-4c165d513a13.png)




## Busca cómo obtener la lista de cards de un board

Request GET:

![image](https://user-images.githubusercontent.com/99162884/167477315-e9b8514f-c52a-4ba8-8b0c-2a157542f587.png)

Cambia valor en la url por el id de tu tablero, ingresa tu TOKEN y KEY API.


![image](https://user-images.githubusercontent.com/99162884/167477414-f24c2d90-ca88-4856-805f-a097be930923.png)

Petición:

![image](https://user-images.githubusercontent.com/99162884/167477477-4fb89e0b-ff95-4e6d-b428-9e390a183cb8.png)


Respuesta(deberás ver la lista de columnas que tienes en tu tablero):

![image](https://user-images.githubusercontent.com/99162884/167477677-580b5f83-8786-450c-a026-edfe93048728.png)


Para el siguiente necesitaremos el ID del primer registro que corresponde a la primer columna.(subrayado de amarillo en la imagen anterior).




##  Busca cómo crear una nueva card en un board

Request POST: 

![image](https://user-images.githubusercontent.com/99162884/167478418-d58ba8c9-e44c-4d27-820b-910f0543fe34.png)

Agrega los parámetros necesario para la peticións: idList(el id de la primer columna del paso anterior), key, token, y name (este es el título de tu card nueva).


![image](https://user-images.githubusercontent.com/99162884/167478835-ae03b2e7-397f-4016-a9da-4cedd0342724.png)


Enviando..

![image](https://user-images.githubusercontent.com/99162884/167479646-f669ec16-bc57-4da0-96fb-5f31e2a6ebe3.png)


Respuesta:

![image](https://user-images.githubusercontent.com/99162884/167479518-7f3ae16b-22c5-4f03-8012-fa7135a4e6a5.png)


Se crea nueva card en mi tablero Trello

![image](https://user-images.githubusercontent.com/99162884/167479770-a8221c31-bc6f-458c-8a02-4615b0d76349.png)



