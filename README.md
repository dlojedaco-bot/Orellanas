# Cultivo de Orellanas — Bruma

App web (PWA) para registrar la siembra, inoculación y cosecha de orellanas,
conectada a Airtable. Se instala en el celular como una app normal.

## Archivos
- `index.html` — la aplicación.
- `manifest.webmanifest` — datos de la app (nombre, color, íconos).
- `sw.js` — service worker (permite instalarla y que abra sin internet).
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — íconos.

## Publicar gratis en GitHub Pages
1. Crea un repositorio nuevo (público) en github.com.
2. Sube todos estos archivos a la raíz del repo.
3. Settings → Pages → Source: rama `main`, carpeta `/root`. Guarda.
4. En un minuto queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Instalar en el celular
- Android (Chrome): abre el enlace → menú ⋮ → **Instalar aplicación**.
- iPhone (Safari): abre el enlace → **Compartir** → **Agregar a inicio**.

## Nota de seguridad
El token de Airtable NO está en el código: se escribe en la pestaña Ajustes
y se guarda solo en tu dispositivo. Por eso es seguro publicar esto en un
repo público. Aun así, no pegues tu token en ningún archivo que subas.
