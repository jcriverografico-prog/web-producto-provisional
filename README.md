# Rivero. — Universo de marcas (prototipo)

Prototipo provisional para clase: una web que se explora en lugar de leerse.
El punto de **Rivero.** es el sol, y cada planeta es una marca.

- **Motos Julio** — marca real (motosjulio.es)
- **Nómada Sur** — marca ficticia, con la Tierra, la Luna y el cohete

## Navegación

Tres niveles: universo → planeta → luna. Cada vista tiene su propio enlace:

- `#universo`
- `#motos-julio`, `#motos-julio--web`, `#motos-julio--tienda`, `#motos-julio--fichas`
- `#nomada-sur`, `#nomada-sur--luna`, `#nomada-sur--branding`, `#nomada-sur--web`, `#nomada-sur--redes`

Con el teclado: ← → para cambiar y Esc para subir un nivel.

## Técnica

Web estática: un `index.html` con Three.js r128 incluido en `js/` y las texturas en `tex/`.
Identidad Rivero.: papel #F7F7F5, tinta #2A2A2A, negro para el logo, cobalto #1E3A8A como único acento, Montserrat y una retícula de 1 px tipo plano técnico.

## Publicar

GitHub → Settings → Pages → Deploy from a branch → `main` / root.
