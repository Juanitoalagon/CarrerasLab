# CarrerasLab

Simulador de carreras de F1 visto desde arriba: temporadas, escuderías, pilotos, academia de redes neuronales…

Se juega en el navegador y se puede **instalar como app** (pantalla completa, sin barra del navegador, funciona sin conexión).

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | El juego entero |
| `manifest.webmanifest` | Nombre, icono y pantalla completa de la app instalada |
| `sw.js` | Guarda el juego en el aparato para que funcione sin conexión |
| `icon-*.png`, `apple-touch-icon.png` | Iconos |
| `partida.json` | Partida incluida: se ofrece cargarla la primera vez que se abre el juego en un aparato nuevo |

## Actualizar el juego

Sustituye `index.html` y `sw.js` por los nuevos. La app instalada baja la versión nueva en segundo plano y la usa la siguiente vez que la abras.
