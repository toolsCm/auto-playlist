AUTO PLAYLIST · UI V5

Esta versión cambia SOLO la interfaz pública.
No modifica Spotify, YouTube, Telegram, KV, programaciones ni el backend.

REEMPLAZA ESTOS ARCHIVOS EN TU PROYECTO:
public/index.html
public/styles.css
public/app.js
public/brand-icon-dark.png
public/brand-icon-light.png
public/favicon.png
public/apple-touch-icon.png

LO QUE CAMBIA
- UI oscura elegante basada en bloques sólidos y sombras suaves.
- Menos transparencia y menos apariencia futurista.
- Icono de archivo + repetir integrado a la marca.
- Fondo con degradado interactivo suave que sigue el puntero.
- Sidebar con navegación hacia las funciones que YA existen.
- Los botones funcionales siguen siendo los mismos:
  * iniciar sesión / cerrar sesión
  * actualizar playlists ahora
  * cargar mes
  * guardar programación
  * actualizar estado
- Spotify, YouTube, Telegram y programación siguen usando exactamente la lógica V4.
- Diseño responsive para celular/tablet.

NO CAMBIES:
src/
wrangler.jsonc
.dev.vars
ni tus secretos de Cloudflare.

PRUEBA LOCAL
npm.cmd run dev:local

PUBLICAR
npx.cmd wrangler deploy
