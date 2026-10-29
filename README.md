# Piedras Geo

Muestrario digital interactivo de 20 minerales y rocas. Incluye búsqueda, filtros por grupo mineralógico y fichas detalladas con fotografías, propiedades e identificación de laboratorio.

## Desarrollo local

Requisitos: Node.js 18 o superior.

```bash
npm install
npm run dev
```

La aplicación estará disponible en `http://localhost:4321`.

## Comprobar la versión de producción

```bash
npm run build
npm run preview
```

El sitio es estático y la salida se genera en `dist/`, por lo que puede publicarse en GitHub Pages, Vercel, Netlify o cualquier hosting estático.

## Subir a GitHub

1. Crea un repositorio vacío en GitHub.
2. Desde esta carpeta ejecuta:

```bash
git add .
git commit -m "Crear muestrario interactivo de minerales"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
git push -u origin main
```

Reemplaza `TU_USUARIO/TU_REPOSITORIO` por los datos de tu repositorio.

## Publicar

Para Vercel o Netlify, importa el repositorio de GitHub y usa estos valores:

- **Build command:** `npm run build`
- **Output directory:** `dist`
- **Install command:** `npm install`

Para GitHub Pages, configura el despliegue de un sitio estático usando `npm run build` y publica el contenido generado en `dist/`.
