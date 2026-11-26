# Rivero. — Universo de marcas (prototipo)

Prototipo provisional para clase: una web que se explora en lugar de leerse.
El punto de **Rivero.** es el sol, y cada planeta es una marca.

- **Motos Julio** — marca real (motosjulio.es). Los logos son propuestas inventadas para el prototipo, no su logo real.
- **Nómada Sur** — marca ficticia. El cohete sale de Rivero. hacia este planeta.

Al entrar hay una intro: bienvenida con el logo de Rivero. y alejamiento hasta ver el sistema.

## Navegación

Tres niveles: universo → marca → sección. Cada vista tiene su propio enlace:

- `#universo`
- `#motos-julio`, `#motos-julio--web`, `#motos-julio--tienda`, `#motos-julio--fichas`
- `#nomada-sur`, `#nomada-sur--branding`, `#nomada-sur--web`, `#nomada-sur--blog`, `#nomada-sur--redes`

En cada marca, el panel permite cambiar entre la propuesta de logo A y B.

Con el teclado: ← → para cambiar y Esc para subir un nivel.

## Técnica

Web estática: un `index.html` con Three.js r128 incluido en `js/` y los logos en PNG en `img/`.
Para cambiar un logo, sustituye el PNG con el mismo nombre (`img/rivero.png` mantiene su proporción 1262×420; los de marca son cuadrados de 600×600 con fondo transparente).
Identidad Rivero.: papel #F7F7F5, tinta #2A2A2A, negro para el logo, cobalto #1E3A8A como único acento, Montserrat y una retícula de 1 px tipo plano técnico.

## Publicar

GitHub → Settings → Pages → Deploy from a branch → `main` / root.
