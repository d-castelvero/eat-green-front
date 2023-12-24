# Eat-green

Es una tienda virtual de alimentos saludables y sustentables para que el consumidor pueda acceder a productos mejores para la salud de manera más sencilla. 


Este proyecto consta de un backend desarrollado en Node.js, la base de datos con MongoDB, y el frontend está desarrollado en React.

Características La aplicación tiene las siguientes funciones:

- Se puede registrar un nuevo consumidor de eat green mediante el formulario de registro
- Se puede ingresar al sitio web como usuario
- Eliminar perfil del usuario
- Editar contraseña del usuario
- Se puede loguear de manera que no necesita volver a hacerlo mientras visita el resto de las secciones 
- Desloguearse cuando lo deseen
- Permite que el usuario envie mensajes
- Borrar el comentario del usuario si lo desean
- Editar el comentario del usuario si lo desean
- Editar o Borrar otros datos en el formulario como (apellido, contraseña o mensaje)
- Permite ver los productos destacados
- Permite conocer sobre la historia de eat green


La base de datos utilizada es MongoDB doende permite almacenar datos importantes para la página web como información sobre el usuario, contraseñas, comentarios,etc.

Se ha utilizado para crear la aplicación:

Express, Mongoose, Bcrypt, Jsonwebtoken, Cors, Dotenv, MongoDB, Node.js
Frontend (React), React Router Dom,  Bootstrap, Axios, react-hot-toast. 




Para instalar la aplicación: 


Backend: 

1. Clona el repositorio con git clone https://github.com/d-castelvero/eat-green-back
2. iniciar npm install para instalar todo lo necesario 
3. Configura las variables de entorno necesarias cmo en el ejemplo

PORT=8000
BASE_URL=http://localhost:8000
DB_URL=mongodb+srv://dcastelvero:Dc456@cluster0.87rnwmn.mongodb.net/?retryWrites=true&w=majority
MONGO_URL = mongodb+srv://dcastelvero:Dc456@cluster0.87rnwmn.mongodb.net/?retryWrites=true&w=majority
JWT_SECRET = eatGreen123456-


4. Antes de iniciar, debe realizar npm install para instalar todo lo necesario
5. Ejecutar el comando "node app.js"

Frontend: 

1. Clona este repositorio en tu máquina local utilizando el siguiente comando. git clone https://github.com/d-castelvero/eat-green-front
2. Realizar npm install antes de iniciar la app 
3. Ejecutar npm run dev

