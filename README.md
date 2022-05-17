# Prueba Técnica - SoyDigi 🚀
### Front End Developer

--------------------------------------------------

### Antes de iniciar

   - Asegúrate de tener [Node.js](https://nodejs.org/es/download/) instalado.
   - deberás de crear una solución utilizando las librerías de [React](https://es.reactjs.org/) y [AntDesign](https://ant.design/docs/react/introduce) para desarrollar el módulo descrito en la prueba.
   - Para simular la integración con el back se sugiere utilizar [Json Server](https://www.npmjs.com/package/json-server), el cual es un módulo que simula solicitudes a un Rest API para enfocarte en el front, a través del módulo se pueden realizar solicitudes *GET*, *POST*, *DELETE*, entre otras. A partir de un archivo JSON.
   - La información de la solución se encontrará en una colección de datos en formato JSON, para poder ser utilizada con **Json Server** con nombre [db.json](./assets/data/db.json).

--------------------------------------------------

### Descripción

El desafío consiste en desarrollar un módulo dentro de una aplicación para la gestión de actividades de personas que trabajan como Freelancers, donde se desea mostrar las interacciones que los Freelancers han tenido con sus diferentes clientes, los cuales están agrupados en *seedbeds*  dependiendo del tipo de cliente. 

para el desarrollo de la prueba se proporcionarán **Wire Frames** del módulo a crear, el cual tendrá dos funcionalidades básicas, explicadas a continuación.

   - la primera funcionalidad es la **gestión de información** en donde se administrarán los datos asociados a los clientes, a partir de solicitudes enviadas al JsonServer API, se deberán de mostrar y desplegar los menús y submenús indicados en el wireframe.

   - la información de los clientes, podrá ser agregada, eliminada o actualizada, dependiendo de la acción realizada por el usuario.
     ![plot](./assets/wireframes/02.png)

   - el menú **Active seedbeds** se deberá de completar a partir de la información retornada por el JsonServer API.

   - la segunda funcionalidad a realizar es el **envío masivo de correos**. A continuación, se muestra la pantalla que dispara un modal para el envío masivo de correos.
     ![plot](./assets/wireframes/03.png)

   - sobre cada grupo de clientes o *seedbeds* mostrados en pantalla, se deberá de **desplegar un modal** mostrando la lista de personas a las que se enviará el correo, junto con el cuerpo de este (en este caso un *lorem ipsum*) 

   - no es necesario realizar el envío del correo, únicamente se debe de simular una solicitud al JsonServer API para que se "encargue" y mostrar el mensaje de envío exitoso, al finalizar se debe de cerrar el modal.

### Funcionalidades del módulo

   - El módulo podrá **filtrar** por varios campos (name, title, etc).

   - El módulo podrá ser **ordenado** por varios campos (name, title, etc).

   - El módulo debe de tener en cuenta la **paginación**, para lo cual se debe de mostrar una lista de clientes con una paginación de 10 elementos, y un botón para cargar más elementos.

   - El prototipo del módulo está diseñado para una interfaz de escritorio, pese a no tener la versión móvil, esté deberá de ser **responsive** para diferentes resoluciones y tamaños de pantalla.

> Para realizar algunas de las funcionalidades descritas anteriormente se recomienda leer la documentación de [Json Server](https://www.npmjs.com/package/json-server)

## User Interface Design (si aplica)
La última parte del desafío es relativa a UI y consiste en aplicar la siguiente guía de marca al módulo desarrollado, creando una Interfaz de Usuario de alta fidelidad accesible (i.e, contraste, legibilidad, etc…)
La familia tipográfica a utilizar es DM Sans, disponible en Google Fonts.

<img width="360" alt="image" src="https://user-images.githubusercontent.com/99594880/165298156-f0194115-1581-4a46-aa69-9fe9ac4d4478.png">

## Al completar el desafío

   - Deberás enviar la solución asociada a un repositorio de **GitHub**, el cual debe de ser **privado** y deberas de darle acceso a la persona que revisará tu solición (usuario: **ArturoHurtado7**) y por ultimo compartir el enlace de la misma con nosostros.

   - Adicionalmente deberás de escribir un archivo **README** junto con las instrucciones detalladas, para correr el programa. 

