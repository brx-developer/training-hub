# 🏋️ Training Hub

**Training Hub** es una aplicación web para registrar y visualizar el progreso de entrenamientos físicos de forma sencilla.
Permite guardar entrenamientos, ver estadísticas clave y analizar el progreso mediante una gráfica interactiva.

---

## 🚀 Funcionalidades

### 📋 Registro de entrenamientos

- Tipo de entrenamiento (Boxeo, Calistenia, etc.)
- Duración en minutos
- Intensidad (1–5)
- Fecha automática
- Persistencia usando **localStorage**

### 📊 Estadísticas dinámicas

- Entrenamientos realizados en la semana actual
- Minutos del último entrenamiento
- Tipo del último entrenamiento

### 📈 Gráfica de progreso

- Gráfica lineal con **Chart.js**
- Filtrado por tipo de entrenamiento
- Datos ordenados por fecha
- Visualización clara del progreso

### 🗂️ Historial

- Tabla con los últimos 20 entrenamientos
- Los más recientes aparecen primero

---

## 🧠 Tecnologías usadas

- Astro
- JavaScript (Vanilla)
- Chart.js
- Tailwind CSS
- localStorage

---

## 📁 Estructura del proyecto

```
src/
├─ components/
│  ├─ Navbar.astro
│  ├─ Footer.astro
│  ├─ StatCard.astro
│
├─ layouts/
│  └─ MainLayout.astro
│
├─ pages/
│  ├─ index.astro
│  └─ progress.astro
│
└─ styles/
   └─ global.css
```

---

## 🧪 Detalles técnicos

- Uso de `Set` para obtener tipos únicos de entrenamiento
- Filtrado y ordenamiento por fecha
- Manejo de estado con localStorage
- Actualización dinámica del DOM
- Límite de registros para mantener rendimiento
- Destrucción segura de gráficos antes de re-renderizar

---

## 🧩 Futuras mejoras (Versión 2)

- Autenticación de usuarios
- Base de datos real
- CRUD completo
- Gráficas avanzadas
- Progreso por usuario

---

## 👤 Autor

**brx-developer**  
Proyecto personal para reforzar lógica, estructura y visualización de datos.

---

## 📝 Nota

Este proyecto corresponde a la **Versión 1** de Training Hub.
