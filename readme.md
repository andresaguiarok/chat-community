# Proyecto Backend

Es un proyecto que se esta realizando este año en la cursada de backend en Coderhouse.\
Este proyecto cuenta con la arquitectura MVC (Modelo-Vista-Controlador) que es un patrón de arquitectura/diseño que separa una aplicación en tres componentes lógicos principales Modelo, Vista y Controlador.\

## Ejecucion de app

Si ejecutas **npm run dev** corre con nodemon\
Si ejecutas **npm run start** corre con node

## Para su uso
Es necesario installar `NODE.JS` & `NODEMON`\
Para el uso del repositorio debe instarlar las siguientes dependencias :

## 1 - `Express`
El proyecto esta programado en este framework backend web transigente, escrito en JavaScript y alojado dentro del entorno de ejecución Node.JS

## 2 - `Express-handlebars`
Es un sistema de plantillas Javascript basado en Mustache Templates. Mantiene separados el código y la vista. Permite generar HTML a partir de objetos con datos en formato JSON\
Cuenta con su propia carpeta que esta asignada como "VIEWS"

## 3 - `socket.io`
El servidor socket.io (basado en Node. js) hace de intermediario entre el iframe y el navegador, de forma que cuando el iframe manda un mensaje en el chat notificará al servidor socket.io, y éste a su vez notificará al navegador para que refresque la página y muestre el mensaje del chat
Cuenta con su vista en la carpeta "VIEWS" y su archivo "chat.handlebars"

## 4 - `bcrypt`
Bcrypt es una función de hash de contraseñas y derivación de claves para contraseñas basada en el cifrado Blowfish\
Su archivo se encuentra en "UTILS"

## 5 - `commander`
Commander se ocupa de analizar los argumentos en opciones y argumentos de comando, muestra los errores de uso para los problemas e implementa un sistema de ayuda\
Se utiliza en combinacion con las variables de entorno para definir en que entorno vamos a desarrollar\ 
Su archivo se encuentra en "UTILS" y su archivo "commander.js"

7 - `connect-mongo`\
8 - `cookie-parser`\
9 - `cors`\
10 - `dotenv`\
11 - `express-session`\
12 - `jsonwebtoken`\
13 - `mongoose`\
14 - `mongoose-paginate-v2`\
15 - `nodemailer`\
16 - `passport`\
17 - `passport-github2`\
18 - `passport-jwt`\
19 - `session-file-store`\
20 - `twilio`\
21 - `uuid`
