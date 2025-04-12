# Descripción del Frontend
El frontend del proyecto está desarrollado con React Native, un framework que permite construir aplicaciones móviles multiplataforma (Android e iOS) utilizando JavaScript y componentes reutilizables. La interfaz permite a los usuarios interactuar con el sistema de forma intuitiva y eficiente.

# Funcionalidades Principales
Pantalla de inicio de sesión (login) con validación de credenciales

CRUD de usuarios: permite crear, consultar, actualizar y eliminar usuarios registrados

Navegación entre pantallas, diseño adaptado a móviles, y consumo eficiente de recursos

# Conexión con el Backend
El frontend se conecta directamente con las rutas del backend Flask alojado en una instancia EC2, utilizando la IP pública del servidor. A través de esta conexión, las acciones realizadas en la app (como registrar un usuario o editar datos) se comunican con el backend, que a su vez actualiza la base de datos MySQL en Amazon RDS.

# Despliegue en la Nube
La aplicación fue desplegada mediante AWS Amplify, una plataforma de desarrollo que facilita el hospedaje y la distribución de aplicaciones móviles y web. Amplify se encargó de compilar y alojar la app, así como de gestionar las conexiones con servicios externos.

# Tecnologías y Herramientas
Framework: React Native

Estado: useState, useEffect, y navegación con React Navigation

Comunicación: Fetch/axios hacia rutas del backend en EC2

Backend conectado a base de datos MySQL en Amazon RDS

Despliegue: AWS Amplify
