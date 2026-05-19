# 🚀 Desplegando una API y Frontend con Docker Compose

Proyecto de ejemplo utilizando:

- PHP
- Phalcon Framework
- Docker
- Docker Compose
- Frontend PHP + Bootstrap
- Arquitectura Multi-Contenedor

Este proyecto muestra cómo desplegar una API y un frontend separados utilizando Docker Compose.

---

# 📚 Objetivos del Proyecto

Este proyecto permite aprender:

✅ Uso de Docker CLI  
✅ Creación de contenedores  
✅ Uso de Docker Compose  
✅ Manejo de imágenes Docker  
✅ Configuración de redes y volúmenes  
✅ Despliegue de aplicaciones PHP  
✅ Comunicación entre contenedores  
✅ Arquitectura Frontend + Backend  

---

# 🏗️ Arquitectura del Proyecto

```text
calificaciones/
│
├── api/
│   ├── Dockerfile
│   ├── .htaccess
│   └── index.php
│
├── frontend/
│   ├── Dockerfile
│   └── index.php
│
└── docker-compose.yml
```

---

# ⚙️ Requisitos

Antes de comenzar debes instalar:

- Docker
- Docker Compose
- Git
- Visual Studio Code (Opcional)

---

# 📥 Clonar el Proyecto

```bash
git clone https://github.com/TU-USUARIO/calificaciones-docker-phalcon.git
cd calificaciones-docker
```

---

# 🚀 Ejecutar el Proyecto

```bash
docker compose up -d
```

---

# 🌐 Acceder a la Aplicación

## API

```text
http://localhost:8080/calification
```

## Frontend

```text
http://localhost:8088
```

---

# 🛑 Detener Contenedores

```bash
docker compose down
```

---

# 📈 Mejoras Futuras

- Base de datos MySQL
- Login de usuarios
- JWT Authentication
- Laravel API
- Vue.js Frontend
- Kubernetes
- CI/CD

---

# 👨‍💻 Autor

**Ing. Mario M. Diaz**
