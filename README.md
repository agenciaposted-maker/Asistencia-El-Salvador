# 📋 Registro de Asistencia — PWA

App para registro de asistencia escolar. Funciona como app instalable en Android e iOS.

## 🚀 Cómo subir a GitHub Pages (paso a paso)

### 1. Crear repositorio en GitHub
1. Ir a [github.com](https://github.com) e iniciar sesión
2. Clic en **"New repository"**
3. Nombre: `asistencia` (o el que quieras)
4. Dejarlo **Public**
5. Clic en **"Create repository"**

### 2. Subir los archivos
En la página del repositorio vacío, clic en **"uploading an existing file"** y sube estos archivos:
```
index.html
manifest.json
sw.js
icons/
  icon-192.png
  icon-512.png
```

### 3. Activar GitHub Pages
1. Ir a **Settings** del repositorio
2. Sección **Pages** (menú izquierdo)
3. En "Branch" seleccionar `main` y carpeta `/ (root)`
4. Clic en **Save**
5. Esperar ~2 minutos y tu app estará en:
   `https://TU-USUARIO.github.io/asistencia/`

## 📱 Instalar en el celular

### Android (Chrome)
- Abrir la URL en Chrome
- Aparece un banner "Instalar app" — tocar **Instalar**
- O: menú ⋮ → "Añadir a pantalla de inicio"

### iPhone/iPad (Safari)
- Abrir la URL en Safari
- Tocar el botón **Compartir** (⬆️)
- Tocar **"Agregar a pantalla de inicio"**
- Tocar **Agregar**

## 💾 Datos
Todos los datos se guardan localmente en el teléfono (localStorage).  
**No se sincronizan entre dispositivos** — cada teléfono tiene su propia base de datos.

## 🏗️ Estructura de archivos
```
├── index.html      ← App completa
├── manifest.json   ← Configuración PWA
├── sw.js           ← Service Worker (modo offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```
