# Heinz Schielmann — Archive Gallery

Static scrollable gallery of all 1,228 Heinz Schielmann pixel-sort artworks.

- `index.html` — dark masonry grid, lazy loading, theme filter chips, caption search, lightbox with Instagram link
- `data.json` — per-image metadata (theme, caption, date, likes, comments, IG url)
- `img/` — 540px JPEGs

Deploy: serve this folder over HTTP (e.g. `docker run -d -p 8099:80 -v $PWD:/usr/share/nginx/html:ro nginx:alpine`) and expose via `tailscale serve`.
