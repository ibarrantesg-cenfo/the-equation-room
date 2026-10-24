# The Equation Room 5.0 — El santuario vivo

Demo experimental 3D de exploración educativa con Three.js.

## Cambios respecto de 4.2
- Avatar procedural mejorado con mochila, brújula, cuerda y detalles faciales.
- Fauna animada estilizada (aves, mariposas), montículos y sendero ceremonial.
- Primer acertijo con **dial físico interactivo**: girar controles en vez de escribir una respuesta.
- Mantiene 5 monumentos, colección de hallazgos, bitácora, brújula y progreso local.

## Iniciar
Publica los archivos en GitHub Pages o sírvelos con un servidor HTTP local (por ejemplo `python -m http.server 8000`). Necesita WebGL y acceso a CDN para Three.js. Abre `index.html` desde el servidor.

## Controles
WASD desplazar, Shift correr, arrastrar ratón girar cámara, E inspeccionar, rueda zoom.

## Limitaciones y siguientes pasos
Damián sigue siendo un modelo procedural sin esqueleto ni animaciones profesionales; el escenario no utiliza aún terreno físico irregular transitable ni colisiones completas con todas las rocas/árboles. Verificar visualmente en navegador y añadir pruebas automatizadas antes de integrar a `main`.
## Recursos gráficos
El retrato provisional de Damián se incluye como SVG en `assets/damian-portrait.svg`, para que el juego no dependa de una imagen ausente. Se sustituirá por el arte definitivo más adelante.
