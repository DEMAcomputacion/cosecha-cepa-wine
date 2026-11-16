# cosecha.cepa.wine

Landing estática de Cepa Cosecha. Sin build: `index.html`, `favicon.svg`, `CNAME`, `.nojekyll`.

## Publicar en GitHub Pages

1. Subí estos archivos a la raíz de un repo (`DEMAcomputacion/cosecha-cepa-wine`), rama `main`.
2. En el repo: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
3. En **Custom domain** poné `cosecha.cepa.wine` (el archivo `CNAME` ya lo trae).
4. En el DNS de `cepa.wine` creá un registro:
   `CNAME  cosecha  →  demacomputacion.github.io`
5. Cuando GitHub valide el dominio, activá **Enforce HTTPS**.

## Para editar

- Email del botón “Sumarme al piloto”: buscá `mailto:hola@cepa.wine` en `index.html`.
- Colores y tipografías: variables CSS al principio del `<style>`.
- La animación del celular está al final del archivo (lista `people`) y se desactiva sola si el usuario pidió reducir movimiento.
