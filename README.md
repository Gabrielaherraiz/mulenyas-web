
# Muleñas — web estática (GitHub Pages)

## Estructura
- `index.html` — Home con hero, lookbook, manifiesto y contacto.
- `404.html` — Página 404 simple.
- `styles.css` — Estilos base.
- `img/hero.png` — Imagen de hero de ejemplo.
- `CNAME` — (opcional) pon aquí tu dominio (p.ej. `mulenyas.com`).

## Pasos para publicar (gratis)
1. Crea un repositorio en GitHub llamado `mulenyas-web`.
2. Sube estos archivos a la raíz del repo (o haz drag&drop).
3. En GitHub → Settings → Pages → "Deploy from a branch" → `main` y `/ (root)`.
4. (Opcional) En Settings → Pages → "Custom domain": escribe tu dominio `mulenyas.com`.
5. En tu registrador configura:
   - `www` → CNAME a `tuusuario.github.io`
   - raíz (apex) → apunta a GitHub Pages (si no puedes, usa Cloudflare DNS con CNAME flattening).
6. Espera la propagación DNS y activa HTTPS (GitHub lo hace automático).
7. En `index.html`, reemplaza `https://formspree.io/f/XXXXXXXX` por tu endpoint real.
