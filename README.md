# Temario-de-aplicaciones-web  

## Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  

## 1. Introducción al desarrollo web  

### Historia y evolución del desarrollo web
El desarrollo web ha evolucionado significativamente desde la creación de la World Wide Web por Tim Berners-Lee en 1989. Inicialmente, los sitios web eran simples documentos de texto estáticos accesibles mediante navegadores básicos. Con el tiempo, la web incorporó imágenes, estilos CSS, interactividad mediante JavaScript y la capacidad de comunicarse con servidores, permitiendo la creación de aplicaciones más complejas. La aparición de frameworks, bibliotecas, y tecnologías como AJAX, HTML5 y CSS3 han marcado hitos importantes en la evolución del desarrollo web.

### Tipos de aplicaciones web
- **Aplicaciones web estáticas**: Son páginas cuyo contenido no cambia en función de la interacción del usuario. Se crean principalmente con HTML y CSS, y su funcionalidad es limitada.
- 
- **Aplicaciones web dinámicas**: El contenido puede cambiar según la interacción del usuario o información proveniente del servidor. Utilizan tecnologías como JavaScript, PHP, Python, bases de datos, etc.
- 
- **SPA (Single Page Application)**: Las aplicaciones de una sola página cargan una única página HTML y actualizan dinámicamente el contenido a medida que el usuario interactúa, sin necesidad de recargar toda la página. Ejemplos: React, Angular, Vue.
- 
- **PWA (Progressive Web Application)**: Son aplicaciones web que ofrecen una experiencia similar a las aplicaciones nativas, incluyendo capacidades offline, notificaciones push y acceso al hardware del dispositivo. Se pueden instalar en el dispositivo del usuario y funcionan incluso sin conexión a internet.

- <img width="200" height="130" alt="image" src="https://github.com/user-attachments/assets/e6d9577f-a5e8-43fa-8524-5601864f91ce" />

## 2. Arquitectura de aplicaciones web

### Cliente-Servidor
El modelo cliente-servidor es la base de la comunicación en aplicaciones web. El cliente (generalmente el navegador web) envía solicitudes al servidor, que procesa la información y responde con datos o recursos. Esta separación permite escalabilidad y una clara división de responsabilidades.

### Arquitectura de tres capas
La arquitectura de tres capas divide la aplicación en tres componentes principales:  

- **Capa de presentación**: Interfaz gráfica o visual con la que interactúa el usuario (HTML/CSS/JavaScript).
- 
- **Capa de lógica de negocio**: Procesa las reglas y operaciones de la aplicación (backend: Node.js, PHP, Python, etc.).
- 
- **Capa de datos**: Gestiona el almacenamiento y recuperación de información (bases de datos como MySQL, MongoDB).

Esta separación facilita el mantenimiento, escalabilidad y reutilización de los componentes.

### REST y API-first design  

- **REST (Representational State Transfer)**: Es un estilo de arquitectura para diseñar servicios web que utilizan los métodos HTTP para acceder y manipular recursos. Permite la comunicación entre aplicaciones de manera sencilla, estandarizada y escalable.
- 
- **API-first design**: Es una filosofía de desarrollo en la que primero se diseña la interfaz de programación de aplicaciones (API) antes de implementar la lógica interna. Esto permite crear sistemas más modulares y facilita la integración con otros servicios y aplicaciones.

## 3. Lenguajes y tecnologías fundamentales

### HTML (HyperText Markup Language)
Es el lenguaje de marcado principal para la creación de páginas web. Define la estructura y el contenido de la web utilizando elementos y etiquetas para texto, imágenes, enlaces, formularios, etc.

### CSS (Cascading Style Sheets)
Permite definir el estilo visual de las páginas web, como colores, fuentes, disposición y diseño adaptable (responsive). Separa la presentación del contenido y facilita el diseño atractivo y profesional de los sitios web.

### JavaScript
Es el lenguaje de programación que proporciona interactividad y dinamismo en la web. Permite manipular el DOM, validar formularios, crear animaciones y desarrollar aplicaciones web completas en el navegador.

### PHP
Lenguaje de programación del lado del servidor ampliamente utilizado para crear páginas web dinámicas. Permite procesar formularios, interactuar con bases de datos y generar contenido personalizado para cada usuario.

### MySQL
Sistema de gestión de bases de datos relacional, frecuentemente utilizado junto con PHP para almacenar y recuperar información de manera eficiente en aplicaciones web, como usuarios, productos, comentarios, etc.

## 4. Control de versiones

### Git y GitHub
Git es un sistema de control de versiones distribuido que permite llevar un historial de los cambios en el código fuente de un proyecto. GitHub es una plataforma basada en Git que facilita la colaboración, el alojamiento de repositorios y la integración de herramientas para el desarrollo web.

### Flujo de trabajo con ramas
El uso de ramas (branching) permite desarrollar nuevas características, corregir errores o experimentar sin afectar la rama principal (main/master) del proyecto. El proceso de trabajo común incluye:

- **Creación de ramas**: Se crea una nueva rama para desarrollar una funcionalidad o corrección específica.
- 
- **Merge (fusión)**: Una vez que los cambios en la rama están listos y probados, se fusionan con la rama principal.
- 
- **Pull Requests**: En plataformas como GitHub, se utiliza un pull request para solicitar la revisión y fusión de los cambios, lo que mejora la colaboración y la calidad del código mediante revisiones por otros miembros del equipo.

- <img width="300" height="180" alt="image" src="https://github.com/user-attachments/assets/d19cbe2f-297f-4579-ab45-7f875d826234" />


# Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

## 1. Diseño e implementación del frontend

### Maquetación, Wireframe y Mockup
El proceso de diseño del frontend comienza con la creación de maquetas, wireframes y mockups para definir la estructura, navegación y aspecto visual de la aplicación antes de desarrollar el código. Estas herramientas ayudan a visualizar la interfaz y mejorar la experiencia de usuario.

### API en el frontend
El frontend puede consumir APIs para interactuar con el backend, obtener y mostrar datos dinámicos, y mejorar la funcionalidad de la aplicación web.

## 2. Diseño e implementación del backend

### Servidor
El backend se encarga de procesar la lógica de negocio, gestionar peticiones y respuestas HTTP, y mantener la seguridad y escalabilidad de la aplicación.

### Manejo de peticiones y respuestas HTTP
El servidor recibe las solicitudes del cliente, las procesa y responde con datos o acciones. Los métodos HTTP más utilizados son GET, POST, PUT y DELETE.

### Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
El backend utiliza sistemas de gestión de bases de datos relacionales como MySQL y PostgreSQL, o bases de datos NoSQL como MongoDB, para almacenar y recuperar datos de manera eficiente.

## 3. Bases de datos

### Modelado de datos y relaciones
El modelado de datos consiste en definir las entidades, atributos y relaciones dentro de la base de datos para asegurar una estructura lógica y funcional.

### ORM (Object Relational Mapping)
Un ORM es una herramienta que permite interactuar con bases de datos mediante objetos en el lenguaje de programación, facilitando el acceso, manipulación y administración de los datos sin escribir consultas SQL directamente.

### CRUD desde el backend
El backend implementa operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para gestionar los datos almacenados en la base de datos de forma eficiente y segura.

## 4. Seguridad básica en aplicaciones web

### Validación de formularios
La validación en el frontend y backend previene la entrada de datos incorrectos o maliciosos, mejorando la seguridad y experiencia del usuario.

### Autenticación y autorización
La autenticación garantiza que solo usuarios válidos accedan al sistema, mientras que la autorización controla los permisos de cada usuario sobre los recursos y funcionalidades de la aplicación.

# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional.  

## 1. Integración de frontend y backend

### Interfaz de usuario Frontend
El frontend proporciona la interfaz gráfica con la que interactúan los usuarios. Utiliza tecnologías como HTML, CSS y JavaScript para mostrar los datos y permitir acciones.

### Manejo de API (API Handling)
La integración se realiza mediante APIs, donde el frontend envía solicitudes (fetch, axios, etc.) al backend y recibe respuestas. Esto permite la comunicación y sincronización de datos entre ambas partes.

### Proceso de Solicitud y Respuesta de Backend
El backend recibe las solicitudes del frontend, las procesa, accede a la base de datos si es necesario y responde con los datos o resultados requeridos por el usuario.

## 2. Almacenamiento en Servidor

### Tipos de servidores
Existen diferentes tipos de servidores según sus funciones y capacidades: servidores web (Apache, Nginx), servidores de aplicaciones, servidores de bases de datos, entre otros.

### Servidores y servicios de hosting
El hosting es el servicio que permite publicar una aplicación web en Internet. Los servicios de hosting pueden ser compartidos, dedicados, VPS o en la nube (cloud hosting).

### Proveedores de servicios de almacenamiento
Entre los principales proveedores se encuentran AWS, Azure, Google Cloud, Heroku y DigitalOcean, cada uno con diferentes soluciones para almacenamiento, bases de datos y despliegue de aplicaciones web.

## 3. Optimización y rendimiento

### Optimización de recursos (imágenes, scripts)
Optimizar imágenes, scripts y recursos estáticos mejora la velocidad y la experiencia del usuario. Se recomienda comprimir imágenes, minificar archivos JavaScript y CSS, y usar técnicas de carga diferida (lazy loading).

### Despliegue de aplicaciones web
El despliegue consiste en publicar la aplicación web en un servidor o servicio de hosting, asegurando que esté accesible para los usuarios finales. Es importante automatizar y documentar este proceso.

### CI/CD básico
La Integración Continua y el Despliegue Continuo (CI/CD) permiten automatizar pruebas y despliegues, asegurando rapidez y confiabilidad en la entrega de nuevas versiones del software.

### Documentación del proyecto
La documentación clara y accesible del proyecto facilita el mantenimiento, la colaboración y el uso por parte de otros desarrolladores y usuarios.


