# Exactly Consulting — sitio web

Sitio estático (HTML/CSS/JS, sin build) de Exactly Consulting, consultora boutique de aviación (Ginebra). Versión v4 aprobada. Idioma del sitio: inglés.

## Estructura
- `index.html` — página única.
- `img/` — fotos, retrato recortado y `logos/` (SVG/PNG).
- `fonts/` — Newsreader y Hanken Grotesk, autoalojadas.

## Previsualizar
```
python3 -m http.server 8000
```
Abrir http://localhost:8000/

## Pendientes
- Quitar `<meta name="robots" content="noindex">` de `index.html` al publicar en el dominio definitivo.
- Backend del formulario de contacto (atributo `data-endpoint`).
- Publicación: Netlify, Vercel o Cloudflare Pages desde este repo; luego dominio `exactlyconsulting.org`.
