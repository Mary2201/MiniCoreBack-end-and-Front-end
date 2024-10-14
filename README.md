# MiniCore: Back-End and Front-End

Este repositorio contiene el backend y el frontend del proyecto **MiniCore**, desarrollado con **Spring Boot** para el backend y **React** para el frontend.


## Descripción

**MiniCore** es una aplicación diseñada para el registro y almacenamiento de notas . El backend se ha desarrollado en **Spring Boot** y el frontend en **React**, permitiendo una arquitectura eficiente y moderna para gestionar.

## Tecnologías Utilizadas

### Backend (Spring Boot)
- **Spring Boot** - Framework principal para el desarrollo del backend.
- **Spring Data JPA** - Para la persistencia de datos.
- **MySQL** - Base de datos 
- **Maven** - Para la gestión de dependencias.

### Frontend (React)
- **React** - Biblioteca para la construcción de interfaces de usuario.
- **Axios** - Para las solicitudes HTTP al backend.
- **React Router** - Para la navegación entre páginas.
- **CSS** - Para el diseño de la interfaz de usuario.

## Instalación

### Backend

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/Mary2201/MiniCoreBack-end-and-Front-end.git
   cd MiniCoreBack-end-and-Front-end/backend
   ```

2. Configurar las dependencias del proyecto con Maven:

   ```bash
   mvn clean install
   ```

3. Ejecutar el servidor de Spring Boot:

   ```bash
   mvn spring-boot:run
   ```

   El servidor estará disponible en `http://localhost:8080`.

### Frontend

1. Cambiar al directorio `frontend`:

   ```bash
   cd ../frontend
   ```

2. Instalar las dependencias de npm:

   ```bash
   npm install
   ```

3. Ejecutar la aplicación React:

   ```bash
   npm start
   ```

   La aplicación se ejecutará en `http://localhost:3000`.

## Despliegue

Para desplegar el backend en Railway:

1. Subir el proyecto de backend a Railway.
2. Configura las variables de entorno necesarias para el despliegue (si aplica).
3. Ejecuta el despliegue directamente desde la consola de Railway.

Para el frontend, puedes utilizar **Vercel**, **Netlify** o cualquier otra plataforma de hosting estático que prefieras.

## Uso

1. Iniciar el backend y el frontend como se describe en la sección de instalación.
2. Acceder a la aplicación desde el navegador en `http://localhost:3000`.
3. Explorar la funcionalidad.
