# Pagina de compra de camisas y publicacion de estampados por parte de artistas

En esta aplicacion se encontrar una pagina que se encarga de vender camisas, conectando el artista que publica los estampados
con el cliente que tiene limites de cantidad y de presupuesto

## Aplicaciones necesarias para el despliegue:

- npm version 9.8.1
- node version 18.18.2
- PostgrSQL version 16.0
- Github desktop (opcional)

## Instrucciones para el despliegue:

### Pasos para importar el proyecto

- Despues de ejecutar Github desktop, clonar el repositorio del link https://github.com/pulidxxx/Pagina-de-compra-de-camisa
- Abrirlo en Visual Studio Code
- Crear una terminal y escribir el comando "npm i"
- Crear una nueva terminal (sin cerrar la anterior) y escribir el comando "npm i"
- Luego tomar el archivo que se llama "config.js" y cambiarle las credenciales para conectar la base de datos
- Luego abrir pgAdmin crear una base de datos llamada "PaginaDeCamisasBD"
- Darle click derecho a la Base de datos > Restore, y seleccionar el archivo llamado "backup.sql" que esta ubicado dentro de la carpeta "database"
- Ahora escribir "npm run dev" en cada una de las terminales

### Pasos para correr las pruebas

- Para correr las pruebas, es necesrio haber corrido el proyecto dem manera exitosa, luego hay que entrar en la terminal en la que se corre el frontend
- Se detiene esa terminal puede ser con "ctrl + c"
- Se escribe el comando "npm test"
