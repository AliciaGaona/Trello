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




## Busca cómo obtener la información de un board a partir de su ID




