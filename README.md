# Frontend - Diego Lechona

Interfaz React y Vite para la API de Diego Lechona.

## Requisitos y desarrollo

- Node.js 20 o superior
- La API disponible en `http://localhost:3000` (el servidor de desarrollo reenvía `/api` a esa dirección)

Instala las dependencias e inicia Vite:

```powershell
npm install
npm run dev
```

Abre `http://localhost:5173`.

## Compilación y despliegue

```powershell
npm run build
```

Publica el contenido de `dist/`. En producción, configura la variable `VITE_API_URL` con la URL base pública de la API, sin añadir `/api` (por ejemplo, `https://mi-api.onrender.com`). Configura en el backend `CORS_ORIGIN` con el origen público exacto del frontend.

Para probar localmente una compilación:

```powershell
npm run preview
```
