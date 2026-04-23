# 🎓 Academia Digital — Sistema Operativo

Sistema de gestión todo-en-uno para tu academia online. Diseñado para dos co-fundadores.

## 🚀 Funcionalidades

- **Dashboard** — Panel de control con cuenta regresiva al lanzamiento
- **Módulos** — Estructura y progreso del curso
- **Parrilla** — Planificación de contenido para redes sociales
- **Temporizador** — Hitos del proyecto
- **Finanzas** — Control de ingresos y gastos
- **Ideas** — Banco de ideas
- **Branding** — Identidad visual de la academia
- **Cambios** — Registro de actividad
- **Ajustes** — Perfiles, temas, sincronización

## 📱 PWA — Instalar como app

En **Android (Chrome)**:
1. Abre la URL de tu GitHub Pages
2. Menú (⋮) → "Añadir a pantalla de inicio"

En **iOS (Safari)**:
1. Abre la URL de tu GitHub Pages
2. Botón compartir → "Añadir a pantalla de inicio"

## 🌐 Deploy en GitHub Pages

1. Sube todos los archivos a un repositorio en GitHub
2. Ve a **Settings → Pages**
3. Source: **Deploy from a branch** → `main` → `/ (root)`
4. Tu app estará en: `https://TU_USUARIO.github.io/NOMBRE_REPO/`

## 📁 Archivos del proyecto

```
├── index.html       # App principal
├── manifest.json    # Config PWA
├── sw.js            # Service Worker (modo offline)
├── icon-192.png     # Ícono app (192x192)
├── icon-512.png     # Ícono app (512x512)
└── README.md        # Este archivo
```

## 🔄 Sincronización entre dispositivos

Los datos se guardan en `localStorage` del navegador.
Para sincronizar entre dos personas:

**Opción 1 — JSON:**
- Exportar datos → compartir archivo por WhatsApp → importar en el otro dispositivo

**Opción 2 — Código:**
- Ajustes → Sincronización → Generar código → copiar y pegar en el otro dispositivo

## 🎨 Temas disponibles

| Tema | Tipo |
|------|------|
| 🔴 Noche Roja | Oscuro |
| 🟣 Galaxia | Oscuro |
| 🟡 Arena | Claro |
| 🟢 Menta | Claro |
