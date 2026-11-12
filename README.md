# Cronômetro de Pallets (PWA)

Avisos por voz e sonoros do tempo restante para cada pallet. Cada jornada (início, fim, nº de pallets) é dividida em slots iguais que seguem o relógio.

## Rodar localmente
```
python3 -m http.server 8000
```
Abra http://localhost:8000 (service worker funciona em localhost).

## Publicar
Hospede os arquivos em HTTPS (GitHub Pages, Netlify ou Cloudflare Pages) e instale pelo navegador.
Ao alterar arquivos, aumente a versão do cache em `sw.js`.
