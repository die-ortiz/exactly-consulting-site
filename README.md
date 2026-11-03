# Exactly Consulting — sitio web

Sitio estático (HTML/CSS/JS, sin build) de Exactly Consulting, consultora boutique de aviación (Ginebra). Versión v9 (en revisión con el cliente). Idioma del sitio: inglés.

## Estructura
- `index.html` — página única.
- `legal-notice.html` y `privacy-policy.html` — aviso legal y política de privacidad (plantilla pendiente de validación del cliente).
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
