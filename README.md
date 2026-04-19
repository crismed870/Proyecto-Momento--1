# Proyecto-Momento--1
# CrisStyle

##  Descripción del Proyecto
CrisStyle es una aplicación web tipo SPA (Single Page Application) desarrollada con React y Vite, que permite a los usuarios explorar un catálogo de zapatos de forma dinámica e interactiva. El proyecto busca ofrecer una solución digital para tiendas de calzado, facilitando la visualización de productos y mejorando la experiencia del usuario.

---

##  Problema que Resuelve
Muchas tiendas de zapatos no cuentan con una plataforma web moderna que permita mostrar sus productos de manera atractiva y organizada. Esta aplicación soluciona este problema ofreciendo:
- Visualización clara de productos
- Navegación rápida sin recargas (SPA)
- Base para futuras funcionalidades como carrito de compras

---

##  Tecnologías Utilizadas
- React
- Vite
- JavaScript (ES6+)
- HTML5
- CSS3
- Node.js
- NPM

---

##  Arquitectura del Proyecto

El proyecto sigue una estructura escalable dentro de `src/`:
src/
│
├── assets/ # Imágenes y recursos
├── components/ # Componentes reutilizables
│ ├── Header.jsx
│ ├── Footer.jsx
│ ├── ProductCard.jsx
│
├── pages/ # Vistas principales
│ ├── Home.jsx
│
├── App.jsx
└── main.jsx


---

##  Componentes Implementados
Se crearon los siguientes componentes funcionales:

- **Header** → Barra de navegación
- **Footer** → Información general
- **ProductCard** → Tarjeta de productos

---

##  Uso de JSX
En el proyecto se implementa:
- Variables dinámicas con `{ }`
- Renderizado de listas
- Uso de `className`
- Importación de imágenes desde `/assets`

---

##  Estilos
Se utilizaron:
- CSS3
- Flexbox para organización
- Diseño limpio y responsive básico

---

##  Proceso de Creación del Proyecto

### 1. Crear el proyecto con Vite
```bash
npm create vite@latest
