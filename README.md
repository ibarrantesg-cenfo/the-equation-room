# The Equation Room 7.0 — La selva olvidada

Primer corte del **rework cinematográfico arqueológico**. La versión 7.0 mantiene las mecánicas y los cinco acertijos de la 6.0 y comienza un cambio de dirección visual hacia un entorno selvático húmedo, misterioso y monumental.

## Implementado en este PR
- Cielo, luz ambiental y niebla más sombríos.
- Troncos derribados, raíces y charcos oscuros en el sotobosque.
- Estelas arqueológicas erosionadas con grabados procedurales.
- Partículas ambientales de esporas/polvo.
- Base existente: cámara en tercera persona, personaje procedural, cinco monumentos matemáticos, minimapa, bitácora y progreso.

## Limitaciones
- **No** es todavía un ecosistema fotorrealista ni un nivel AAA comparable al acabado de juegos comerciales.
- El personaje sigue siendo una composición geométrica, **no** un modelo GLB riggeado.
- Los materiales y la naturaleza siguen siendo procedurales, sin mapas PBR escaneados.
- Faltan pruebas completas en navegador, revisión de rendimiento y test de las soluciones matemáticas.

## Próximos pasos
1. Prueba visual y funcional en GitHub Pages antes de fusionar.
2. Modelos 3D reales y texturas PBR para rocas, barro, ruinas y vegetación.
3. Cámara con colisiones y animaciones profesionales para Damián.
4. Integrar acertijos como mecanismos físicos del escenario.

## Controles
WASD: caminar · Shift: correr · E: interactuar · M: minimapa · P: foto · G: calidad gráfica.

El juego utiliza Three.js vía CDN, por lo que requiere conexión a internet.
