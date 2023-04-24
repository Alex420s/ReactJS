<h1 align = 'center'> ReactJS </h1>

***
Hola, estoy aprendiendo algo de React para poder enseñarte cosas de calidad de la mejor forma.

---

<h2 align = 'center'> SETUP INICIAL  </h2>

Creamos la carpeta que almacenara nuestro proyecto, entramos en ella y creamos nuestra aplicacion `React`.

````
 1.- mkdir curso-react
 2.- cd curso-react
 3.- npx create-react-app curso-react
````
Donde `curso-react` puede el nombre que quieras.
<br/>

A continuacion se creara el directorio `curso-react` los siguientes archivos:

````
    >node_modules
    >public
    >src
    .gitignore
    package-lock.json
    package.json
    README.md
````
### ¿Qué hace cada archivo?:<br/>
`node_modules:` <br>
**Esta carpeta almacena algunos módulos clave para el funcionamiento de nuestra aplicación React.**

`public:` <br>
**En esta carpeta se encuentran los archivos que serán "leidos" por el navegador, aquí se encuentra** <br> *index.html*. **React "inserta" el código en este archivo para que el navegador lo pueda mosrar.**

`src:` <br>
**Aquí es donde "vivirá" el código de la aplicación y pasaremos la mayor parte del tiempo.**

`.gitignore:` <br>
**Este archivo "ignora" ciertas carpetas o archivos que no deseas compartir.**

`package-lock.json:` <br>
**Es parte del manejador de paquetes NPM y sirve para guardar los detalles de sobre configuración del proyecto en caso de querer recrear la aplicación.**

`package.json:` <br>
**Es informacion sobre el "módulo" o paquete, tendrás que llenar algunos campos para poder llenar el formato.**
***
A continuación iniciamos el ambiente de desarrollo con el comando:
> npm start app

Esto iniciará un servidor en el puerto 3000 de nuestro localhost, para acceder a la app "goglea" [localhost:3000](https://localhost:3000)

