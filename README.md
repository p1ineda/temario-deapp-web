# temario-deapp-web
# temario-deapp-web
< ins > 1.-Introducción al desarrollo web < ims >


Historia y evolución del desarrollo web.
## 1. Historia y evolución del desarrollo web
<img width="279" height="154" alt="image" src="https://github.com/user-attachments/assets/4ea1d808-f707-495b-bcfe-12af413e91c3" />

El desarrollo web ha evolucionado significativamente desde la creación de la World Wide Web en 1989 por Tim Berners-Lee. Inicialmente, las páginas web eran estáticas y solo contenían texto y enlaces. Con el tiempo, se introdujeron nuevas tecnologías, lo que permitió agregar imágenes, formularios y estilos.

-  ** Década de los 90 ** : HTML básico, páginas estáticas, aparición de CSS y JavaScript.
-  ** años 2000 ** : Web dinámica con PHP, ASP, MySQL, surgimiento de CMS como WordPress.
-  ** Década de 2010 ** : Llegada de frameworks JavaScript (Angular, React, Vue), aparición de SPA y PWA, auge del desarrollo móvil.
-  ** Actualidad ** : API-first design, microservicios, Jamstack, automatización CI/CD, integración con IA.



Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)
## 2. Tipos de aplicaciones web
<img width="266" height="157" alt="image" src="https://github.com/user-attachments/assets/ce60938e-7693-4e0e-a5dc-790ff3b168a8" />

Las aplicaciones web se clasifican según su funcionamiento y experiencia de usuario:

-  ** Estáticas ** : El contenido no cambia, se sirve tal cual está almacenado en el servidor (ej. páginas informativas en HTML).
-  ** Dinámicas ** : El contenido se genera en función de la interacción del usuario o datos almacenados (ej. foros, tiendas online).
-  ** SPA (Aplicación de página única) ** : Aplicaciones de una sola página, el contenido se actualiza dinámicamente sin recargar toda la página. Ejemplo: Gmail, Trello.
-  ** PWA (Progressive Web App) ** : Aplicaciones web que ofrecen experiencia similar a las apps móviles, con capacidad offline, notificaciones push y posibilidad de instalarse en dispositivos.

-

2.Arquitectura de aplicaciones web
Cliente-Servidor
Arquitectura de tres capas (presentación, lógica, datos)
Diseño REST y API-first
## 3. Arquitectura de aplicaciones web
<img width="289" height="137" alt="image" src="https://github.com/user-attachments/assets/68116f43-fee3-4f8c-aaa7-933a2b2d4ece" />

Las aplicaciones web se estructuran en diferentes arquitecturas para optimizar su funcionamiento y escalabilidad:

### Cliente-Servidor
Modelo básico donde el cliente (navegador) solicita información al servidor, y este responde con los datos o páginas solicitadas.

### Arquitectura de tres capas
-  ** Presentación ** : Interfaz con la que interactúa el usuario (HTML, CSS, JS).
-  ** Lógica de negocio ** : Procesa las reglas de negocio y la interacción entre presentación y datos (PHP, Node.js, Python).
-  ** Datos ** : Sistema de almacenamiento y recuperación de información (MySQL, MongoDB).

### Diseño REST y API-first
-  ** REST (Transferencia de estado representacional) ** : Estilo de arquitectura que utiliza HTTP y recursos identificados por URL. Facilitar la interoperabilidad entre sistemas.
-  ** API-first Design ** : Enfoque donde la API se diseña primero, permitiendo que el frontend y backend se desarrollen de manera independiente y escalable.
3 . -Lenguajes y tecnologías fundamentales
HTML, CSS, JavaScript, PHP, MySQL
## 4. Lenguajes y tecnologías fundamentales

-  ** HTML (Lenguaje de marcado de hipertexto) ** : Estructura básica de la web.
-  ** CSS (Cascading Style Sheets) ** : Define la apariencia y el diseño de las páginas web.
-  ** JavaScript ** : Lenguaje para la interactividad y lógica del lado del cliente.
-  ** PHP ** : Lenguaje de servidor para crear aplicaciones web dinámicas.
-  ** MySQL ** : Sistema de gestión de bases de datos relacionales, usado junto con PHP.


4.-Control de versiones
Git y GitHub
Flujo de trabajo con ramas (ramificación, fusión, aplicaciones de extracción)
## 5. Control de versiones
<img width="282" height="144" alt="image" src="https://github.com/user-attachments/assets/120d653e-30e1-48a3-a11a-95ff0ed96a7f" />

El control de versiones es esencial para el desarrollo colaborativo y la gestión de cambios en proyectos web.

### Git y GitHub
-  ** Git ** : Sistema distribuido de control de versiones. Permite gestionar el historial de cambios y trabajar en equipo.
-  ** GitHub ** : Plataforma basada en Git para alojar, colaborar y gestionar proyectos de software.

### Flujo de trabajo con ramas
-  ** Branching ** : Crear ramas para desarrollar funcionalidades o corregir errores sin afectar el código principal.
-  ** Merge ** : Combinar los cambios realizados en diferentes ramas.
-  ** Pull Requests ** : Solicitud para integrar los cambios de una rama a la rama principal, facilitando la revisión y colaboración.



Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
1.-Diseño e implementación del frontend
Maqueta/Wireframe/Mockup
API
## 1. Diseño e implementación del frontend
<img width="339" height="133" alt="image" src="https://github.com/user-attachments/assets/80d70d22-0445-4214-b058-d3efce7089d7" />

El ** frontend ** es la parte de la aplicación web con la que interactúa el usuario. Su diseño y desarrollo incluye:

### Maquetación, Wireframe y Mockup
-  ** Maquetación ** : Proceso de organizar los elementos visuales en la página mediante HTML y CSS. Defina la estructura y el diseño.
-  ** Wireframe ** : Esquema básico (boceto) de la distribución de los componentes en la interfaz sin detalles visuales.
-  ** Mockup ** : Representación visual detallada del producto final, incluye colores, tipografía y estilos.

### API
- El frontend consume datos de una ** API ** (Interfaz de Programación de Aplicaciones) para mostrar información dinámica y realizar acciones como formularios, búsquedas y actualizaciones en tiempo real.



2.-Diseño e implementación del backend
Servidor
Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
## 2. Diseño e implementación del backend
<img width="273" height="150" alt="image" src="https://github.com/user-attachments/assets/c53245ab-f5af-4618-8e6e-087ddf8a42fc" />

El ** backend ** es la parte lógica y funcional de la aplicación, encargada de procesar datos, manejar solicitudes y conectarse a bases de datos.

### Servidor
- El servidor ejecuta el código backend (por ejemplo, Node.js, PHP, Python) y responde a las solicitudes del cliente.

### Manejo de peticiones y respuestas HTTP
- El backend recibe ** peticiones HTTP ** (GET, POST, PUT, DELETE) y genera respuestas (HTML, JSON, XML) para el cliente.
- Se utilizan frameworks como Express (Node.js), Django (Python), Laravel (PHP) para facilitar este proceso.

### Conexión a bases de datos
- El backend se conecta a bases de datos como ** MySQL ** , ** PostgreSQL ** (relacionales) o ** MongoDB ** (NoSQL) para almacenar y recuperar datos.



3.-Bases de datos
Modelado de datos y relaciones
ORM (Mapeo relacional de objetos)
CRUD desde el backend
## 3. Bases de datos
<img width="300" height="147" alt="image" src="https://github.com/user-attachments/assets/6ace8c66-898a-4efb-b4e1-471bc1f76728" />

Las bases de datos son fundamentales para guardar información y permitir su acceso eficiente.

### Modelado de datos y relaciones
- Definir las entidades y sus relaciones (uno a uno, uno a muchos, muchos a muchos).
- Ejemplo: Usuarios y publicaciones, donde un usuario puede tener varias publicaciones.

### ORM (Mapeo relacional de objetos)
- Permite interactuar con la base de datos usando objetos en el lenguaje de programación.
-Ejemplos : ** SQLAlchemy ** (Python), ** Eloquent ** (Laravel), ** TypeORM ** (Node.js).

### CRUD desde el backend
-  ** CRUD ** (Crear, Leer, Actualizar, Eliminar): Operaciones básicas para manipular datos desde el backend a través de endpoints y controladores.

-
4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización
## 4. Seguridad básica en aplicaciones web
<img width="317" height="128" alt="image" src="https://github.com/user-attachments/assets/89906e81-037f-445f-b67d-6e7e49eb0a2f" />

La seguridad es esencial para proteger datos y usuarios.

### Validación de formularios
- Verificar que los datos enviados por el usuario cumplen con los requisitos (tipo, formato, longitud).
- Prevenir ataques como ** inyección SQL ** y ** XSS ** (Cross Site Scripting).

### Autenticación y autorización
-  ** Autenticación ** : Verificar la identidad del usuario (login con usuario y contraseña, tokens JWT).
-  ** Autorización ** : Determinar qué acciones puede realizar el usuario según su rol (admin, usuario común).

-  

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1 . -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend
## 1. Integración de frontend y backend
<img width="265" height="159" alt="image" src="https://github.com/user-attachments/assets/bc0aefda-dfeb-4dba-813a-6f3f98188b15" />

La integración del frontend y backend es fundamental para lograr una aplicación web funcional que brinde una experiencia completa al usuario.

### Interfaz de usuario Frontend
Consiste en el desarrollo de la parte visual y de interacción de la aplicación utilizando tecnologías como HTML, CSS y JavaScript. El frontend se encarga de mostrar datos, captar entradas del usuario y enviar solicitudes al backend.

### Manejo de API
El frontend se comunica con el backend mediante API, principalmente a través de protocolos como HTTP. Las API permiten que el frontend obtenga y envíe datos, normalmente en formato JSON, utilizando métodos como GET, POST, PUT y DELETE.

### Proceso de Solicitud y Respuesta de Backend
El backend recibe las solicitudes del frontend, procesa la información, se conecta con la base de datos si es necesario y devuelve una respuesta adecuada. El flujo consiste en:
- El usuario interactúa con la interfaz.
- El frontend envía una solicitud a la API del backend.
- El backend procesa la solicitud y responde con los datos o el resultado de la operación.
- El frontend actualiza la interfaz según la respuesta recibida

2.- Almacenamiento en Servidor
<img width="293" height="153" alt="image" src="https://github.com/user-attachments/assets/7264bc64-e206-4243-a41e-483b1091779f" />

Tipos de servidores
Servidores y servicios de hosting
Proveedores de Servicios de Almacenamiento
El almacenamiento y despliegue en servidores permite que la aplicación esté disponible para los usuarios.

### Tipos de servidores
-  ** Servidor local ** : Utilizado para desarrollo y pruebas (ejemplo: XAMPP, WAMP, Localhost).
-  ** Servidor dedicado ** : Exclusivo para un solo proyecto o cliente, brinda mayor control y rendimiento.
-  ** Servidor compartido ** : Varios proyectos comparten recursos, es más económico pero con recursos limitados.
-  ** Servidor en la nube ** : Recursos escalables y flexibles, acceso global (ejemplo: AWS, Azure, Google Cloud).

### Servidores y servicios de hosting
-  ** Hosting tradicional ** : Empresas como GoDaddy, Bluehost ofrecen alojamiento web para aplicaciones estáticas y dinámicas.
-  ** Hosting especializado ** : Plataformas modernas como Heroku, Vercel, Netlify, que automatizan el despliegue y escalabilidad.
-  ** Servicios de contenedores ** : Uso de Docker y Kubernetes para aplicaciones más complejas.

### Proveedores de Servicios de Almacenamiento
-  ** Amazon Web Services (AWS) ** : Ofrece servicios como S3 (almacenamiento de archivos), EC2 (servidores virtuales), RDS (bases de datos).
-  ** Google Cloud Platform (GCP) ** : Proporciona Compute Engine, Cloud Storage, Firestore.
-  ** Microsoft Azure ** : Soluciones como Blob Storage, App Service, SQL Database.
-  ** Otros proveedores ** : DigitalOcean, Linode, Firebase, que ofrecen opciones para proyectos de distintos tamaños.

---

3.-Optimización y rendimiento
<img width="272" height="158" alt="image" src="https://github.com/user-attachments/assets/f58ab55e-eb12-40c5-8600-ae9cb0a1d1e4" />

Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto
Para asegurar una experiencia rápida y eficiente, la optimización y el rendimiento son aspectos clave.

### Optimización de recursos (imágenes, scripts)
-  ** Compresión de imágenes ** : Usar formatos modernos como WebP, ajustar resolución y calidad.
-  ** Minificación de scripts y estilos ** : Reducir el tamaño de archivos CSS y JS eliminando espacios y comentarios.
-  ** Carga diferida (lazy loading) ** : Cargar imágenes y recursos solo cuando se necesita.
-  ** Uso de CDN (Content Delivery Network) ** : Distribuir archivos estáticos desde servidores cercanos al usuario.

### Despliegue de aplicaciones web
- Publicar la aplicación en un entorno de producción usando servicios como Vercel, Netlify, Heroku, AWS.
- Configurar dominios, certificados SSL y variables de entorno.
- Realizar pruebas antes y después del despliegue para asegurar el correcto funcionamiento.

### CI/CD básico
-  ** CI (Integración Continua) ** : Automatizar la integración de cambios en el código mediante pruebas automáticas.
-  ** CD (Despliegue Continuo) ** : Automatizar la entrega y publicación de la aplicación tras pasar las pruebas.
- Herramientas populares: GitHub Actions, GitLab CI/CD, Jenkins.
- Beneficios: Mayor calidad de código, despliegues rápidos y seguros, reducción de errores humanos.

### Documentación del proyecto
- Crear y mantener documentación clara sobre la arquitectura, uso de la API, procesos de implementación, dependencias y configuración.
- Usar archivos README.md, documentación de endpoints con Swagger y comentarios en el código.
- Facilitar el mantenimiento, colaboración y escalabilidad del proyecto.
