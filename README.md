# Seguridad Inteligente - Centro de Monitoreo

Página web interactiva basada en las imágenes enviadas: mapa de vigilancia, cámaras, drones, alertas, reportes, historial y configuración.

## Cómo ejecutar en tu PC

1. Instala Node.js.
2. Abre esta carpeta en Visual Studio Code.
3. En la terminal escribe:

```bash
npm install
npm run dev
```

4. Abre el enlace que salga, normalmente: `http://localhost:5173`.

## Qué debes subir a GitHub

Sube TODO lo que está dentro de esta carpeta:

- `index.html`
- `package.json`
- `README.md`
- carpeta `src/`
  - `main.jsx`
  - `styles.css`

No subas `node_modules`, esa carpeta se crea sola con `npm install`.

## Cómo alojarlo en Vercel

1. Sube la carpeta a GitHub.
2. Entra a Vercel y elige **Add New Project**.
3. Selecciona tu repositorio.
4. Configuración:
   - Framework Preset: **Vite**
   - Build Command: `npm run build`
   - Output Directory: `dist`
5. Clic en **Deploy**.

## Importante

Este proyecto es un prototipo frontend totalmente interactivo con datos simulados. Para cámaras/drones reales se debe conectar después a una API/backend, WebRTC/RTSP o servicios de streaming.
