# Neurología · Hub de estudio (PWA)

App de estudio offline: 24 temas, 176 bloques y 3.251 preguntas basadas solo en el PDF de la asignatura.

## Publicar en GitHub Pages
1. Crea un repositorio y sube el contenido de esta carpeta a la raíz (`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`, `.nojekyll`).
2. En *Settings → Pages* elige la rama `main` y la carpeta `/ (root)`.
3. Abre `https://<usuario>.github.io/<repo>/` y usa *Añadir a pantalla de inicio* (iOS: Compartir; Android: menú ⋮ → Instalar app).

El service worker guarda la app en caché tras la primera visita y funciona sin conexión. El progreso se guarda en `localStorage` del navegador.
Para actualizar contenido, sustituye `index.html` y sube el número de `CACHE` en `sw.js` (por ejemplo `neuro-hub-v2`).
