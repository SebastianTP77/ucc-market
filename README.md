# 🛒 ucc-market  
Realización Proyecto UCC-MARKET

---

## 📖 Descripción General

**UCC-MARKET** es una plataforma web tipo marketplace especializada en la **compra y venta de productos tecnológicos**, tanto nuevos como usados.  
Su propósito es ofrecer un entorno **seguro, moderno y eficiente**, donde los usuarios puedan **publicar, buscar, comprar o vender** artículos como computadores, componentes, periféricos, celulares, accesorios y más.

Este proyecto se desarrolla bajo la **metodología ágil Scrum**, promoviendo el trabajo colaborativo entre los cursos de **Computación en la Nube** y **Desarrollo Web y Móviles** de la **Universidad Cooperativa de Colombia**.

---

## 🎯 Objetivos del Proyecto

### 🔹 Objetivo General
Construir una **plataforma web funcional y escalable** que facilite la interacción entre compradores y vendedores de productos tecnológicos, aplicando principios de diseño moderno, seguridad, escalabilidad y metodologías ágiles.

### 🔹 Objetivos Específicos
- Diseñar una arquitectura modular frontend-backend.
- Gestionar usuarios con roles diferenciados (comprador, vendedor, administrador).
- Permitir publicación, búsqueda y administración de productos.
- Integrar pasarelas de pago (simuladas o reales).
- Desplegar la aplicación en la nube (Azure, AWS o GCP).
- Documentar el proyecto en un repositorio organizado.
- Aplicar Scrum con roles definidos y entregas por sprint.

---

## 🧩 Arquitectura y Tecnologías

### 🖥️ Frontend
- Frameworks: React, Vue.js o Angular  
- Responsive design  
- Gestión de estado: Redux, Pinia o Context API

### 🔧 Backend
- Lenguajes: Node.js + Express o Python (Django/FastAPI)  
- API RESTful  
- Base de datos: PostgreSQL, MySQL o MongoDB  
- Seguridad: JWT, CORS, validación de datos

### ☁️ Cloud & DevOps
- Docker y Docker Compose  
- CI/CD con GitHub Actions  
- Despliegue en Azure, AWS o GCP  
- Manejo de variables con `.env`

---

## 🧠 Componentes del Proyecto

El repositorio está organizado en las siguientes carpetas:

- `backend/`: Lógica del servidor, controladores, modelos, rutas, autenticación y conexión a base de datos.
- `frontend/`: Interfaz gráfica del usuario, componentes, vistas, formularios y gestión del carrito.
- `mobile/`: Aplicación móvil en Flutter o React Native para dispositivos Android/iOS.
- `cloud/`: Archivos de despliegue en la nube, Dockerfile, docker-compose.yml y scripts de CI/CD.
- `docs/`: Documentación técnica, diagramas UML, plan Scrum, referencia de API.
- `.env.example`: Variables de entorno de ejemplo.
- `LICENSE`: Licencia del proyecto (MIT).
- `README.md`: Documentación principal del repositorio.

---

## ⚙️ Requisitos Técnicos

- Node.js >= 18 / Python >= 3.10  
- Docker y Docker Compose  
- Git  
- Cuenta en proveedor cloud  
- Navegador moderno compatible con ES6+

---

## 🚀 Metodología Scrum

- **Product Owner:** Define requerimientos y prioridades  
- **Scrum Master:** Facilita el proceso y remueve impedimentos  
- **Equipo de Desarrollo:** Implementa funcionalidades por sprint

Cada sprint dura **2 semanas** e incluye:
1. Planificación  
2. Desarrollo  
3. Revisión  
4. Retrospectiva

---

## 🧪 Pruebas y Calidad

- Pruebas unitarias e integración: Jest / PyTest  
- Validación de API: Postman  
- CI/CD: GitHub Actions  
- Análisis estático y revisión de dependencias

---

## ☁️ Despliegue

- Contenedores Docker para cada servicio  
- Orquestación con Docker Compose o Kubernetes  
- Escalabilidad y tolerancia a fallos

---

## 🛡️ Seguridad

- Autenticación con JWT  
- Cifrado de contraseñas con bcrypt  
- Protección CORS, CSRF  
- HTTPS con certificados TLS

---

## 🧾 Licencia

Distribuido bajo la licencia **MIT**

---

## 👥 Autores y Colaboradores

- Equipo de Computación en la Nube  
- Equipo de Desarrollo Web y Móviles  
- Universidad Cooperativa de Colombia 🟢

---

## 🧰 Comandos Básicos

### Clonar el repositorio:
```bash
git clone https://github.com/usuario/ucc-market.git
