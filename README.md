# 🏍️ Repuestos Motos Store

Plataforma de e-commerce moderna para la venta de repuestos de motos. Construida con React, Node.js y MongoDB.

## 🎯 Características

- ✅ Catálogo de productos dinámico
- ✅ Carrito de compras
- ✅ Sistema de pedidos
- ✅ Gestión de usuarios
- ✅ Búsqueda y filtros avanzados
- ✅ Galería de imágenes
- ✅ Información de contacto y ubicación
- ✅ Interfaz móvil-first
- ✅ Diseño moderno y corporativo

## 🛠️ Tecnologías

### Frontend
- **React** - Librería UI
- **Vite** - Bundler rápido
- **Tailwind CSS** - Estilos modernos
- **React Router** - Navegación
- **Axios** - Cliente HTTP

### Backend
- **Node.js** - Runtime JavaScript
- **Express** - Framework web
- **MongoDB** - Base de datos
- **JWT** - Autenticación

## 📁 Estructura del Proyecto

```
repuestos-motos-store/
├── frontend/                 # Aplicación React
│   ├── src/
│   │   ├── components/      # Componentes reutilizables
│   │   ├── pages/           # Páginas principales
│   │   ├── context/         # Context API (carrito, usuario)
│   │   ├── services/        # Llamadas API
│   │   ├── styles/          # Estilos globales
│   │   └── App.jsx
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── backend/                  # API Node.js
│   ├── src/
│   │   ├── models/          # Modelos MongoDB
│   │   ├── routes/          # Rutas API
│   │   ├── controllers/     # Lógica de negocio
│   │   ├── middleware/      # Autenticación, validación
│   │   └── server.js
│   ├── package.json
│   └── .env.example
│
├── docs/                     # Documentación
├── .gitignore
└── package.json (root)
```

## 🚀 Quick Start

### Requisitos
- Node.js v16+
- npm o yarn
- MongoDB (local o MongoDB Atlas)

### Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/pampalogistica3-beep/repuestos-motos-store.git
cd repuestos-motos-store
```

2. **Configurar Backend**
```bash
cd backend
npm install
cp .env.example .env
# Edita .env con tus credenciales
npm run dev
```

3. **Configurar Frontend**
```bash
cd frontend
npm install
npm run dev
```

4. **Acceder**
- Frontend: http://localhost:5173
- API: http://localhost:5000

## 📚 Documentación

- [Guía de Instalación](./docs/INSTALACION.md)
- [API Endpoints](./docs/API.md)
- [Estructura del Proyecto](./docs/ESTRUCTURA.md)

## 📧 Contacto

Email: info@repuestos-motos.com

## 📄 Licencia

MIT License - Libre para uso comercial

---

**Creado con ❤️ para los amantes de las motos**
