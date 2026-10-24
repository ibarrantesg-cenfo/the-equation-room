# THE EQUATION ROOM 6.0 · El corazón de Nébara

Aventura matemática 3D en tercera persona creada para FUN-02.

## Funcionalidades
- Cinco acertijos conectados a obeliscos arqueológicos y mecanismo numérico interactivo.
- Ecosistema selvático con relieve, varios estratos de vegetación, fauna, ruinas, torre de observación, ambientación y agua.
- Damián Vela: avatar procedural articulado con sombrero, mochila y equipo arqueológico (no es un GLB riggeado profesional).
- Cámara en tercera persona, WASD, sprint y examen de reliquias.
- Minimapa táctico, brújula, modo fotografía y selector de calidad.
- Cuatro hallazgos de historia ambiental, bitácora y guardado local de posición y progreso.

## Controles
WASD para caminar, Mayús para correr, E para examinar, ratón para cámara, rueda para zoom, M para alternar minimapa, P para foto, G para calidad.

## Ejecución
Servir mediante GitHub Pages o servidor estático. Usa Three.js mediante jsDelivr: **requiere acceso a internet**. Recomendado Chrome/Edge en PC con WebGL.

## Restricciones conocidas
- Modelo procedural todavía lejos del aspecto cinematográfico de un personaje GLB con rig y animaciones.
- La selva sigue siendo procedural, y puede exigir ajustes de rendimiento en móviles.
- La física del río y las colisiones complejas no están implementadas.
- Validación algebraica mejorable; revisar equivalencias y dominio.

## Verificación
La sintaxis del módulo JavaScript se comprueba con `node --check`. Además se realizan pruebas automatizadas de carga en Chromium y capturas de pantalla siempre que esté disponible el CDN.