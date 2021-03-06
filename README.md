# Prueba T茅cnica - SoyDigi 馃殌
### Front End Developer

--------------------------------------------------

### Antes de iniciar

   - Aseg煤rate de tener [Node.js](https://nodejs.org/es/download/) instalado.
   - deber谩s de crear una soluci贸n utilizando las librer铆as de [React](https://es.reactjs.org/) y [AntDesign](https://ant.design/docs/react/introduce) para desarrollar el m贸dulo descrito en la prueba.
   - Para simular la integraci贸n con el back se sugiere utilizar [Json Server](https://www.npmjs.com/package/json-server), el cual es un m贸dulo que simula solicitudes a un Rest API para enfocarte en el front, a trav茅s del m贸dulo se pueden realizar solicitudes *GET*, *POST*, *DELETE*, entre otras. A partir de un archivo JSON.
   - La informaci贸n de la soluci贸n se encontrar谩 en una colecci贸n de datos en formato JSON, para poder ser utilizada con **Json Server** con nombre [db.json](./assets/data/db.json).

--------------------------------------------------

### Descripci贸n

El desaf铆o consiste en desarrollar un m贸dulo dentro de una aplicaci贸n para la gesti贸n de actividades de personas que trabajan como Freelancers, donde se desea mostrar las interacciones que los Freelancers han tenido con sus diferentes clientes, los cuales est谩n agrupados en *seedbeds*  dependiendo del tipo de cliente. 

para el desarrollo de la prueba se proporcionar谩n **Wire Frames** del m贸dulo a crear, el cual tendr谩 dos funcionalidades b谩sicas, explicadas a continuaci贸n.

   - la primera funcionalidad es la **gesti贸n de informaci贸n** en donde se administrar谩n los datos asociados a los clientes, a partir de solicitudes enviadas al JsonServer API, se deber谩n de mostrar y desplegar los men煤s y submen煤s indicados en el wireframe.

   - la informaci贸n de los clientes, podr谩 ser agregada, eliminada o actualizada, dependiendo de la acci贸n realizada por el usuario.
     ![plot](./assets/wireframes/02.png)

   - el men煤 **Active seedbeds** se deber谩 de completar a partir de la informaci贸n retornada por el JsonServer API.

   - la segunda funcionalidad a realizar es el **env铆o masivo de correos**. A continuaci贸n, se muestra la pantalla que dispara un modal para el env铆o masivo de correos.
     ![plot](./assets/wireframes/03.png)

   - sobre cada grupo de clientes o *seedbeds* mostrados en pantalla, se deber谩 de **desplegar un modal** mostrando la lista de personas a las que se enviar谩 el correo, junto con el cuerpo de este (en este caso un *lorem ipsum*) 

   - no es necesario realizar el env铆o del correo, 煤nicamente se debe de simular una solicitud al JsonServer API para que se "encargue" y mostrar el mensaje de env铆o exitoso, al finalizar se debe de cerrar el modal.

### Funcionalidades del m贸dulo

   - El m贸dulo podr谩 **filtrar** por varios campos (name, title, etc).

   - El m贸dulo podr谩 ser **ordenado** por varios campos (name, title, etc).

   - El m贸dulo debe de tener en cuenta la **paginaci贸n**, para lo cual se debe de mostrar una lista de clientes con una paginaci贸n de 10 elementos, y un bot贸n para cargar m谩s elementos.

   - El prototipo del m贸dulo est谩 dise帽ado para una interfaz de escritorio, pese a no tener la versi贸n m贸vil, est茅 deber谩 de ser **responsive** para diferentes resoluciones y tama帽os de pantalla.

> Para realizar algunas de las funcionalidades descritas anteriormente se recomienda leer la documentaci贸n de [Json Server](https://www.npmjs.com/package/json-server)

## User Interface Design (si aplica)
La 煤ltima parte del desaf铆o es relativa a UI y consiste en aplicar la siguiente gu铆a de marca al m贸dulo desarrollado, creando una Interfaz de Usuario de alta fidelidad accesible (i.e, contraste, legibilidad, etc鈥?)
La familia tipogr谩fica a utilizar es DM Sans, disponible en Google Fonts.

<img width="360" alt="image" src="https://user-images.githubusercontent.com/99594880/165298156-f0194115-1581-4a46-aa69-9fe9ac4d4478.png">

## Al completar el desaf铆o

   - Deber谩s enviar la soluci贸n asociada a un repositorio de **GitHub**, el cual debe de ser **privado** y deberas de darle acceso a la persona que revisar谩 tu solici贸n (usuario: **ArturoHurtado7**) y por ultimo compartir el enlace de la misma con nosostros.

   - Adicionalmente deber谩s de escribir un archivo **README** junto con las instrucciones detalladas, para correr el programa. 

