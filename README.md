# API de Usuarios (CRUD) con Node.js, Express y MongoDB

Este proyecto implementa una **API RESTful de gestión de usuarios** que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre una colección de usuarios utilizando **Node.js**, **Express** y **MongoDB**.

---

## 🧰 Funcionalidades principales

- Crear un nuevo usuario (POST)  
- Obtener la lista de todos los usuarios (GET)  
- Obtener los datos de un usuario específico por ID (GET)  
- Actualizar los datos de un usuario (PUT/PATCH)  
- Eliminar un usuario (DELETE)  
- Validación básica de datos  
- Conexión con base de datos MongoDB mediante Mongoose  

---

## 🛠 Tecnologías utilizadas

- Node.js  
- Express  
- MongoDB  
- Mongoose  
- dotenv (variables de entorno)  
- (Opcional) nodemon para desarrollo  

---

## Instalación

1.- Clonar el repositorio
```bash
git clone git@github.com:UrbanoTrejoOrlando/API-User-CRUD-Node-JS-Express-MongoDB.git
```
2.- Navegar al directorio del proyecto
```bash
cd API-User-CRUD-Node-JS-Express-MongoDB
```
3.- Instala las dependencias
```bash
npm install
```
4.- Inicia el servidor
- En **modo desarrollo**
```bash
npm run dev
```
- En **modo producción**
```bash
npm start
```

## Rutas de la API

| Método | Ruta         | Descripción                    |
|--------|--------------|--------------------------------|
| POST   | `/users`     | Crear un nuevo usuario         |
| GET    | `/users`     | Obtener todos los usuarios     |
| GET    | `/username/:username` | Obtener un usuario por el nombre de usuario   |
| GET    | `/users/:id` | Obtener un usuario por el id |
| PUT | `/users/:id` | Editar un usuario             |
| DELETE | `/users/:id` | Eliminar un usuario             |
