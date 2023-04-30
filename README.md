# Default Node.js MongoDB Server

Este es un servidor Express básico con una conexión MongoDB establecida. Puedes agregar algunas operaciones de base de datos a este servidor para adaptarlo a tus necesidades.

## Pasos para empezar

### 0. Configurar variables de entorno

Cree un archivo llamado en la carpeta raiz .env y agregue el siguiente texto:

```env
MONGO_URI=mongodb://127.0.0.1:27017/?directConnection=true&serverSelectionTimeoutMS=2000
PORT=3000
```

### 1. Instalar las dependencias requeridas

En primer lugar, necesitas instalar los paquetes básicos necesarios. Puedes hacerlo ejecutando este comando:

```bash
npm install 

### 2. Iniciar el servidor

Para iniciar el servidor, ejecuta el siguiente comando en la terminal:

```bash
node index.js
```

### 3. Probar el servidor

Abre tu navegador web e ingresa la siguiente URL: http://localhost:3000. Esto debería mostrar una página web básica que indica que el servidor se está ejecutando correctamente.

Para probar la ruta /users, ingresa a la siguiente URL: http://localhost:3000/users. Esta ruta te permitirá acceder a la colección "users" en tu base de datos MongoDB.

## Audiencia

Este documento está dirigido a desarrolladores que buscan configurar un servidor básico con Express y MongoDB. Si eres nuevo en el desarrollo web o no estás familiarizado con estas tecnologías, te recomendamos buscar recursos adicionales para complementar esta documentación.
