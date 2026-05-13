#  Blog 

Aplicación web de blogging desarrollada con Node.js, Express y EJS, enfocada en la renderización dinámica de contenido y la organización modular del backend.

El proyecto implementa una arquitectura ligera pero escalable utilizando plantillas EJS, manejo de rutas en Express y persistencia de datos con MongoDB mediante Mongoose.

Diseñado como una base sólida para sistemas de publicación de contenido, permitiendo una estructura flexible y mantenible para futuras funcionalidades.

---

#  Features

- 📰 Sistema dinámico de publicaciones
- 🃏 Renderizado reutilizable mediante partials EJS
- 🔎 Filtrado y organización visual de contenido
- ⚡ Server-Side Rendering (SSR)
- 🌐 Backend server con Express.js
- 🗄️ Persistencia de datos con MongoDB + Mongoose
- 📦 Arquitectura modular orientada a escalabilidad
- 🎨 Separación entre lógica, vistas y modelos
- 🔧 Configuración mediante variables de entorno
- 📱 Base preparada para futuras mejoras y expansión

---

# 🛠️ Stack Tecnológico

## Backend
- Node.js
- Express.js
- Body-parser
- Mongoose
- MongoDB

## Frontend
- EJS
- JavaScript
- HTML5
- CSS3

---

# 📂 Estructura del Proyecto

```bash
blog/
│
├── img/
│
├── src/
│   ├── models/
│   │   └── blog.js
│   │
│   └── views/
│       ├── _create.ejs
│       ├── _edit.ejs
│       ├── _footer.ejs
│       └── ...
│
├── index.js
├── package.json
└── .env
```

La estructura del proyecto fue organizada para mantener una clara separación entre modelos de datos, vistas renderizadas y lógica del servidor, facilitando el mantenimiento y futuras integraciones.

---

# ⚙️ Instalación

## 1. Clonar el repositorio

```bash
git clone https://github.com/smarchena/blog.git
```

## 2. Instalar dependencias

```bash
npm install
```

## 3. Crear archivo `.env`

Para habilitar la conexión con MongoDB, es necesario crear un archivo `.env` en la raíz del proyecto.

Ejemplo:

```env
MONGODB_URI=your_mongodb_connection
PORT=3000
```

---

# ▶️ Ejecutar el Proyecto

```bash
npm start
```

o en entorno de desarrollo:

```bash
npm run dev
o
npx nodemon index.js
```

---

# 🧠 Conceptos Aplicados

- Server-side rendering con EJS
- Arquitectura modular en Node.js
- Manejo de rutas y middleware
- Modelado de datos con Mongoose
- Separación de responsabilidades
- Integración backend/frontend
- Renderizado dinámico de vistas

---

# 📈 Roadmap

- Sistema de autenticación
- Panel administrativo
- Upload de imágenes
- Comentarios y reacciones
- API REST
- Sistema de búsqueda avanzada
- Optimización SEO

---

# 👨‍💻 Author

Developed by Santiago M.
