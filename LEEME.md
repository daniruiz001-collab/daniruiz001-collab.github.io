# Contexto · Lo viral, explicado

Web estática: `index.html` + `ads.txt`. No necesita servidor ni compilación.

## Activar los anuncios remunerados (Google AdSense)
1. Publica la web en un dominio propio (Netlify, Vercel, GitHub Pages o Cloudflare Pages, todos gratis).
2. Date de alta en https://adsense.google.com y añade el dominio.
3. Sustituye `ca-pub-XXXXXXXXXXXXXXXX` en `index.html` y `pub-XXXXXXXXXXXXXXXX` en `ads.txt` por tu ID.
4. Descomenta la etiqueta `<script ... adsbygoogle.js>` del `<head>`.
5. Crea en AdSense 5 bloques de anuncio y pon sus IDs en los `data-ad-slot` (1111111111 … 5555555555).
6. UE/España: activa el mensaje de consentimiento GDPR (CMP) en AdSense > Privacidad y mensajes.
7. Rellena las páginas de Privacidad, Cookies y Aviso legal (las exige la LSSI y AdSense).

## Actualización semanal
Cada artículo es un bloque `<article>` con: Qué pasó · Lectura sociológica · Perspectiva histórica · Nivel de evidencia · Fuentes.
