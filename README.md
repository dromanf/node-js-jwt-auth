# Node.js – JWT Prueba con autenticación y autorización con JSONWebToken & Sequelize

## Proceso de registro, inicio de sesión de usuario y autorización.
El diagrama muestra el flujo de cómo implementamos el proceso de registro de usuario, inicio de sesión de usuario y autorización.

# Rutas:
POST /api/auth/signup	registrar una nueva cuenta
POST /api/auth/signin	iniciar sesión
GET	 /api/test/all	recuperar contenido público
GET	 /api/test/user	acceder al contenido del usuario
GET	 /api/test/mod	acceder al contenido del moderador
GET	 /api/test/admin	acceder al contenido del administrador

## Project setup
```
npm install
```

### Run
```
node server.js
```