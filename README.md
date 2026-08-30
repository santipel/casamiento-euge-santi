# Euge & Santi — Casamiento 💍

Página web de casamiento, sitio estático (sin build ni dependencias).

## Estructura

```
.
├── index.html         # Toda la página (HTML + CSS + JS inline)
└── imagenes/           # Fotos e ilustraciones referenciadas por index.html
```

## Cómo editarlo

Es un solo archivo HTML. Se puede abrir directo en el navegador (doble click)
para previsualizar cambios sin necesidad de servidor ni de subir nada.

## Backend (RSVP)

El formulario de confirmación de asistencia manda los datos a un Google Apps
Script (no incluido en este repo), que lee/escribe en un Google Sheet.
Los endpoints están hardcodeados en `index.html` (buscar `ENDPOINT`).

## Deploy

Este sitio está pensado para hosting estático (Netlify, Vercel, GitHub Pages,
Cloudflare Pages, etc.) — no necesita servidor ni proceso de build. Basta con
subir la carpeta tal cual.

Ver instrucciones de dominio + hosting más abajo (o preguntá).
