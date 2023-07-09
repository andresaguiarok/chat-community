# Proyecto Backend

Es un proyecto que se esta realizando este año en la cursada de backend en Coderhouse.\
Este proyecto cuenta con la arquitectura MVC (Modelo-Vista-Controlador) que es un patrón de arquitectura/diseño que separa una aplicación en tres componentes lógicos principales Modelo, Vista y Controlador.

## Ejecucion de app

Si ejecutas **npm run dev** corre con nodemon.\
Si ejecutas **npm run start** corre con node.

## Para su uso
Es necesario installar `NODE.JS` & `NODEMON`\
Para el uso del repositorio debe instarlar las siguientes dependencias :

## 1 - `Express`
El proyecto esta programado en este framework backend web transigente, escrito en JavaScript y alojado dentro del entorno de ejecución Node.JS

## 2 - `Express-handlebars`
Es un sistema de plantillas Javascript basado en Mustache Templates. Mantiene separados el código y la vista. Permite generar HTML a partir de objetos con datos en formato JSON.\
Cuenta con su propia carpeta que esta asignada como "views"

## 3 - `socket.io`
El servidor socket.io (basado en Node. js) hace de intermediario entre el iframe y el navegador, de forma que cuando el iframe manda un mensaje en el chat notificará al servidor socket.io, y éste a su vez notificará al navegador para que refresque la página y muestre el mensaje del chat
Cuenta con su vista en la carpeta "views" y su archivo "chat.handlebars"

## 4 - `bcrypt`
Bcrypt es una función de hash de contraseñas y derivación de claves para contraseñas basada en el cifrado Blowfish\
Su archivo se encuentra en "utils"

## 5 - `commander`
Commander se ocupa de analizar los argumentos en opciones y argumentos de comando, muestra los errores de uso para los problemas e implementa un sistema de ayuda\
Se utiliza en combinacion con las variables de entorno para definir en que entorno vamos a desarrollar\ 
Su archivo se encuentra en "utils" y su archivo "commander.js"

## 6 - `connect-mongo`
Nuestra configuración de session require este modulo para sabes cuando el usuario inicia su session
Se encuentra inicializado en `APP.JS`

## 7 - `cookie-parser`
Cookie-parser analiza el encabezado Cookie y rellena req.cookies con objeto marcado con los nombres de las cookies.
Se encuentra inicializado en `APP.JS` y trabaja en conjunto con el archivo "jsonWebToken.js" que se encuentrsa en la carpeta "utils" &
con el archivo "passportJWT.js" que se encuentra en la capera "passportJwt" 

## 8 - `cors`
Intercambio de Recursos de Origen Cruzado (CORS) es una característica de seguridad del navegador que restringe las solicitudes HTTP de origen cruzado que se inician desde secuencias de comandos que se ejecutan en el navegador.
Se encuentra inicializado en `APP.JS`

## 9 - `dotenv`
Se require dotenv para manejar las variables de entorno con las que se desarrolla\
Se encuentra en ".env" , ".env.development" & ".env.production"

## 10 - `express-session`
El middleware express-session almacena los datos de sesión en el servidor , se encuentra inicializado en `APP.JS`

## 11 - `jsonwebtoken`
JSON Web Token (JWT) es un estándar para transmitir información de forma segura en internet, por medio de archivos en formato JSON
Su archivo "jsonWebToken.js" que se encuentra en la capera "utils" 

## 12 - `mongoose`
Mongoose es una biblioteca de modelado de datos orientada a objetos (ODM) para MongoDB y Node. js. Administra las relaciones entre los datos, proporciona validación de esquemas y se utiliza para traducir entre objetos en el código y la representación de esos objetos en MongoDB.\
Los archivos con los que se desarrollan se encuentran en las carpetas " dao > models > " y son los siguientes:\
*1 - cartModel.js
*2 - messageModel.js
*3 - productModel.js
*4 - ticketModel.js
*5 - userModel.js

## 13 - `mongoose-paginate-v2`
mongoose-paginate-v2 es una biblioteca de paginación que tiene un contenedor de página. El uso principal del complemento es que puede modificar las claves de valor de retorno directamente en la consulta misma para que no necesite ningún código adicional para la transformación.\
Trabaja en conjunto con el archivo "productModel.js" que se encuentra en la carpetas " dao > models > "

## 15 - `nodemailer`
Es un paquete de distribución de Node. js que podemos integrar a nuestro proyecto y nos permite enviar email a un servidor SMTP en formato texto o HTML.\
Se desarrolla con variables de entorno que se encuentan en ".env.development" & ".env.production".\
Cuenta con su propio archivo "nodeMailer.js" que se encuentra en la carpeta "utils".\
Y trabaja en conjunto con el archivo "cartsController.js" que se ecuentra en la carpeta "controllers".

## 16 - `passport`


17 - `passport-github2`\
18 - `passport-jwt`\
19 - `session-file-store`\
20 - `twilio`\
21 - `uuid`
