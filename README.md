# 8th Wall AR - ProyectoAR

Experiencia WebAR con image target **edificio-img** y modelo 3D **edificio_5.glb**.

- La raíz del repositorio es el build HTML5 listo para publicar (Vercel/Netlify).
- `source/` contiene el proyecto editable de 8th Wall Desktop (sin `node_modules`).

## Deploy en Vercel

1. Importa este repositorio en Vercel.
2. Framework Preset: **Other**.
3. Build Command: dejar vacío.
4. Output Directory: `.` (raíz).
5. Deploy.

Abre la URL resultante en el celular y permite la cámara. El target a escanear es
`source/image-targets/edificio-img_original.png` (o la imagen original del edificio).

## Desarrollo local

```bash
cd source
npm install
npm run serve
```

Requiere 8th Wall Desktop para editar la escena visualmente.
