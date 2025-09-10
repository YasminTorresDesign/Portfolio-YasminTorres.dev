---
title: App Mobiliario
publishDate: 2024-06-09 00:00:00
img: /assets/tu_mueble-1.png
img_alt: Bienvenido a Tu_mueble, mobiliario CNC
description: |
  TU MUEBLE es una aplicación web que ofrece soluciones de diseño de muebles para ser armados en casa. Permite a los usuarios buscar, personalizar y descargar mobiliario digital de manera intuitiva y sencilla.
tags:
  - SpringBoot
  - Java
  - MySql
  - Thymeleaf
  - Figma
---


## Acerca de este proyecto

> Convierte tus Ideas en realidad.   Descarga,imprime y construye tus Propios Muebles Personalizados

Los usuarios pueden descargar archivos desde la página para cortarlos por sí mismos en un taller externo con una máquina CNC o con un carpintero local.
TU MUEBLE está optimizada para funcionar en cualquier dispositivo, ya sea un ordenador, una tablet o un smartphone, se adapta dinámicamente a diferentes tamaños de pantalla, asegurando una experiencia de usuario fluida

---

### Prototipo
El prototipado en el desarrollo de software comienza con un dibujo rápido antes de empezar a codificar. Es importante porque nos ayuda a entender cómo será el software antes de hacerlo realmente.
Se ha utilizado la herramienta **Figma** que permite realizar los wireframes, mockups y prototipos que al agregarle interactividad se puede tener una idea más clara de la funcionalidad del proyecto.

#### Prototipo movil
![Arquitectura Astro](/assets/prot-movil.png)

https://www.figma.com/proto/iULylnS9KOiFAY6iwt8wNh/appTuMueble?type=design&node-id=213-3505&t=AORy3WhWfyeOWrjJ-0&scaling=scale-down&page-id=213%3A2251&starting-point-node-id=213%3A3505


#### Prototipo desktop
![Arquitectura Astro](/assets/prot-desktop.png)

https://www.figma.com/proto/iULylnS9KOiFAY6iwt8wNh/appTuMueble?type=design&node-id=221-3839&t=AORy3WhWfyeOWrjJ-0&scaling=scale-down&page-id=221%3A3830&starting-point-node-id=221%3A3839

---

### Arquitectura Tecnológica

La arquitectura tecnológica se basa en una arquitectura de tres capas:
1. **Capa de Presentación (Frontend):** Desarrollada utilizando Angular para construir una
interfaz de usuario interactiva y amigable.

2. **Capa de Lógica de Negocio (Backend):** Implementada en Spring Boot, que proporciona
la lógica de negocio, la gestión de usuarios, la personalización de productos, la gestión de pedidos
y otras funcionalidades.

3. **Capa de Almacenamiento de Datos (Base de Datos):** Utiliza MySQL como sistema de
gestión de base de datos relacional para almacenar la información de usuarios, productos,
pedidos, etc.

----

### Frameworks Utilizados
Se ha definido el conjunto de tecnologías que se utilizarán para el desarrollo de la
aplicación, dividido en dos áreas principales: Front-End y Back-End.

#### Desarrollo del Front-End
El Front-End se centrará en la parte visual de la aplicación, aquella que interactuarán
directamente los usuarios. Para esto, se utilizarán las siguientes tecnologías:
- **HTML:** Para la estructura básica de las páginas web.
- **CSS:** Para el diseño y estilo de los elementos de la interfaz.
- **JavaScript:** Para la interactividad y funcionalidades dinámicas de la aplicación.
- **Thymeleaf:** Motor de plantillas Java del lado del servidor diseñado para entornos web e independientes. 

#### Desarrollo del Back-End
El Back-End se encargará de la lógica de negocio, el manejo de datos y la seguridad de la
aplicación. Para esto, se utilizarán las siguientes tecnologías:

- **Java:** Como lenguaje de programación principal, conocido por su versatilidad y robustez
en el desarrollo de aplicaciones empresariales.
- **Spring Boot:** Como framework de desarrollo para Java, que proporciona
herramientas y funcionalidades para la creación rápida de aplicaciones web y servicios RESTful. 

#### Gestor de Base de Datos
El tipo de base de datos es relacional. Las estructuras de los datos se organizan en tablas
que están interrelacionadas mediante claves primarias y foráneas.
El gestor de base de datos utilizado es **MySQL,** que es un sistema de gestión de bases
de datos relacional de código abierto que es ampliamente utilizado para el desarrollo de
aplicaciones web y empresariales. 


### Estándares
- **RESTful API:** La aplicación "TU MUEBLE" sigue el principio de arquitectura REST
(Representational State Transfer) para la exposición de servicios web. Esto
significa que se utilizan los métodos HTTP estándar (GET, POST, PUT, DELETE)
para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en los recursos
de la aplicación, lo que proporciona una interfaz uniforme y fácil de usar para la
comunicación entre el cliente y el servidor.

- **JSON (JavaScript Object Notation):** Se utiliza JSON como formato de intercambio
de datos entre el frontend y el backend de la aplicación. JSON es un formato ligero
y fácil de leer que facilita la transmisión y el análisis de datos estructurados entre
los diferentes componentes de la aplicación.

- **MVC (Modelo-Vista-Controlador):** La arquitectura de la aplicación sigue el patrón
de diseño MVC, que separa los datos de la aplicación (Modelo), la lógica de
presentación (Vista) y la lógica de control (Controlador). Esta separación de
responsabilidades facilita la mantenibilidad y la escalabilidad del código, así como
la reutilización de componentes.

- **Seguridad Web:** Se implementan prácticas de seguridad web estándar, como la
autenticación y la autorización, para proteger los recursos y datos sensibles de la
aplicación. Se utilizan tokens de acceso JWT (JSON Web Tokens) para gestionar
la autenticación de usuarios y se aplican filtros de seguridad en las rutas protegidas
para garantizar que solo los usuarios autorizados puedan acceder a ciertas
funcionalidades.

 
### Desafíos
El principal desafío fue la aplicacion y adopción de nuevas tecnologías y frameworks. También lo fue la integracion del fronted con el backend y la base de datos, que todo se ejecutara exitosamente.

### Aprendizajes
Este proyecto reforzó los conocimientos aprendidos en un proyecto funcional y dinamico. La importancia del control de versiones del proyecto por medio de la herramienta **GITHUB**.

---

#### Aqui estamos

- <a href=" https://yasmintorresdesign.my.canva.site/manual-usuario-web-store">Manual de Usuario 🌐 </a>
- <a href=" https://www.youtube.com/watch?v=wand9VRd6y0">Video Tutorial 🌐 </a>
- <a href="https://github.com/YasminTorresDesign/web-store">Ver codigo 💻 </a>

---
 
