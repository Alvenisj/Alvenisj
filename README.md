![logo-finalllllll](https://github.com/Alvenisj/Alvenisj/assets/58892711/d7ab414a-d4c8-47bc-aa3d-d00e6f9df6ac=1024x)
### **👋 Hello 👋 My name is  ALVENIS BECERRA**
   I am a -Systems Engineer- Full-time experience working with technologies such as: 
  * Developed and maintained backend services using Node.js and Express.js.
  * Designed and implemented RESTful APIs to support frontend applications.
  * Integrated MongoDB and SQL databases to store and retrieve data efficiently.
  * Collaborated with frontend developers to create responsive and interactive user interfaces using React.js.
  * Implemented automated testing and continuous integration to ensure code quality and reliability. <br/>
  
#  &bull; **Technologies:**

[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white&labelColor=101010)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=101010)](https://www.mongodb.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=101010)](https://www.mysql.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/Alvenisj)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=101010)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=101010)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=101010)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![API Restful](https://img.shields.io/badge/API%20Restful-2F2625?style=for-the-badge&logo=rest&logoColor=white&labelColor=101010)](https://restfulapi.net/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=101010)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=101010)](https://www.typescriptlang.org/)
[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white&labelColor=101010)](https://www.microsoft.com/en-us/windows)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black&labelColor=101010)](https://www.linux.org/)
[![Apple](https://img.shields.io/badge/Apple-999999?style=for-the-badge&logo=apple&logoColor=white&labelColor=101010)](https://www.apple.com/)
[![Inteligencia Artificial](https://img.shields.io/badge/Inteligencia_Artificial-FF5733?style=for-the-badge&logo=ai&logoColor=white&labelColor=101010)](https://en.wikipedia.org/wiki/Artificial_intelligence)


#  &bull; **Experiences:**
![img33](https://github.com/Alvenisj/Alvenisj/assets/58892711/9c7f2e37-80a2-4be2-8aca-2cd214f9169f)


#  - **Information**
- **Email:** Alvenisj@gmail.com --> [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:Alvenisj@gmail.com) 
- **LinkedIn:** [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/alvenis-becerra-ingenieria-sistemas)
- **GitHub:** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/Alvenisj)

## Projects Menu

1. [![Ir al sitio Web Proyecto 1](https://img.shields.io/badge/Sitio%20Web-Proyecto%201-blue)](https://lissethvieraterapeutaocupacional.up.railway.app/)

2. [![Ir al sitio Web Proyecto 2](https://img.shields.io/badge/Sitio%20Web-Proyecto%202-green)](https://alvenisj.github.io/app-genalcaWeb/)

3. [![Ir al sitio Web Proyecto 3](https://img.shields.io/badge/Sitio%20Web-Proyecto%203-yellow)](https://alvenisj.github.io/app-paginationJs/)

4. [![Ir al sitio Web Proyecto 4](https://img.shields.io/badge/Sitio%20Web-Proyecto%204-orange)](https://alvenisj.github.io/app-ventanaModalJavascript/)

5. [![Ir al sitio Web Proyecto 5](https://img.shields.io/badge/Sitio%20Web-Proyecto%205-red)](https://alvenisj.github.io/formularioEnvioEmailJavascript/)

6. [![Ir al sitio Web Proyecto 6](https://img.shields.io/badge/Sitio%20Web-Proyecto%206-purple)](https://alvenisj.github.io/app-dinamicMenuWeb/)

## Usage of Node.js in Your Project 
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white&labelColor=101010)](https://nodejs.org/)
Node.js is a JavaScript runtime environment based on Google Chrome's V8 engine. Here are some of the key features of Node.js in this project:
- **Express Server**: We use Express.js, a popular Node.js framework, to create a robust and scalable web server.
- **Package Management with npm**: npm, the Node.js package manager, is used to manage project dependencies and facilitate the installation of external libraries and modules.
- **Middleware**: Express.js allows us to utilize middleware to effectively handle HTTP requests, such as routing middleware, body parsing, authentication, etc.
- **Database Connection**: Node.js enables us to connect to various databases, such as MongoDB, MySQL, PostgreSQL, etc., to store and retrieve data efficiently.
- **RESTful API**: We utilize Node.js to create a RESTful API that provides endpoints for clients to interact with the server and access data.

#  - **Example Code of Node.js with Express:**
``` Node Js
// Importar Express
import express from 'express';

// Crear una instancia de Express
const app = express();

// Definir una ruta de inicio
app.get('/', (req, res) => {
  res.send('¡Hola mundo desde Express!');
});

// Definir una ruta de ejemplo con parámetros
app.get('/saludo/:nombre', (req, res) => {
  const { nombre } = req.params;
  res.send(`¡Hola, ${nombre}!`);
});

// Definir una ruta de ejemplo con método POST
app.post('/mensaje', (req, res) => {
  res.send('Mensaje recibido correctamente.');
});

// Escuchar en un puerto específico
const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
  console.log(`Servidor Express funcionando en el puerto ${PORT}`);
});

```


## Usage of MongoDB in Your Project
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=101010)]()
MongoDB is a NoSQL database, offering a flexible schema design that allows us to store and manage unstructured or semi-structured data efficiently. This flexibility is particularly advantageous for projects with evolving data requirements or complex data models.


#  - **Install MongoDB in your Proyect** [![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=101010)]()
``` mongoDB
  npm install mongodb
```

#  - **Install Typescript** [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=101010)](https://www.typescriptlang.org/)
``` Typescript
  npm install -D typescript
```
# React.js Frontend [![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=101010)](https://reactjs.org/)

```jsx
import React from 'react';

// Definir un componente funcional usando una función de flecha y fragmentos
const MiComponente = () => (
  <>
    <h1>Hola Mundo desde React</h1>
    <p>Este es un ejemplo corto de código en React.</p>
  </>
);

export default MiComponente;

```

#  - **HTML code** [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=101010)](https://developer.mozilla.org/en-US/docs/Web/HTML)
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Mi Sitio Web</title>
    </head>
    <body>
 	 <header>
	    <h1>Mi Sitio Web</h1>
	    <nav>
		      <ul>
		        <li><a href="#">Inicio</a></li>
		        <li><a href="#">Acerca de</a></li>
		        <li><a href="#">Servicios</a></li>
		        <li><a href="#">Contacto</a></li>
		      </ul>
	    </nav>

    </header>
    
  <main>
	    <section>
		      <h2>Acerca de Nosotros</h2>
		      <p>Somos una empresa comprometida con la calidad y la innovación...</p>
	    </section>
	    <section>
		      <h2>Nuestros Servicios</h2>
		      <ul>
		        <li>Servicio 1</li>
		        <li>Servicio 2</li>
		        <li>Servicio 3</li>
		      </ul>
	    </section>
  </main>

  <footer>
    &copy; 2024 Mi Sitio Web
  </footer>

</body>
</html>
```
