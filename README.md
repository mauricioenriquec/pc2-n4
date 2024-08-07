# Sistema de Autenticación con JWT

Este proyecto implementa un sistema de autenticación utilizando JSON Web Tokens (JWT) en una aplicación Node.js con Express.js. La aplicación incluye la funcionalidad de expiración de tokens para mejorar la seguridad.

## Configuración Inicial

1. Clona el repositorio o descarga los archivos del proyecto.
2. Instala las dependencias necesarias ejecutando `npm install`.
3. Configura las variables de entorno en el archivo `.env`:

   ```plaintext
   JWT_SECRET=your_jwt_secret_key
   JWT_EXPIRES_IN=1800 # Tiempo de expiración en segundos (30 minutos)
