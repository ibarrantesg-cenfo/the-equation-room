# The Equation Room — La ruta de Nébara

Videojuego educativo de aventura arqueológica, desarrollado para practicar conceptos de Lógica y Matemática Básica (FUN-02).

## Estado actual

**Prototipo 4.0:** experiencia de exploración en primera persona con perspectiva 3D simulada (raycasting), artefactos interactivos, acertijos algebraicos, narración, sonidos generados mediante Web Audio y protagonista ilustrado, Damián Vela.

> Importante: el personaje existe como arte conceptual 2D integrado a la interfaz y la introducción. Aún **no es un modelo 3D animado controlable**; la selva exterior tampoco se ha implementado.

## Jugar en local

Abrir `index.html` directamente en un navegador moderno. No utiliza dependencias externas ni necesita instalar paquetes. También puedes usar un servidor estático:

```bash
python -m http.server 8000
```

Y abrir `http://localhost:8000`.

## Controles

- WASD: caminar.
- Flechas / arrastrar ratón: girar.
- E: inspeccionar un artefacto cercano.
- Botón de audio: iniciar/detener ambiente sonoro tras la interacción inicial.

## Contenido educativo

Cinco mecanismos con valor numérico, combinación de términos semejantes, productos notables, polinomios y simplificación racional con restricciones de dominio. Los nombres de los temas **no se anuncian al jugador** en los acertijos.

## Organización

- `index.html`: prototipo jugable y lógica actual.
- `assets/`: retratos e imágenes originales del personaje creadas para el proyecto.
- `docs/ROADMAP.md`: plan de trabajo y visión 3D.
- `docs/QUALITY.md`: deuda técnica y pruebas.

## Próximas metas

1. Migrar el monolito a módulos (`src/engine`, `src/world`, `src/puzzles`, `src/audio`, `src/ui`).
2. Diseñar malla 3D original de Damián (`.glb`) con rig, caminar, correr e interactuar.
3. Selva explorable con vegetación, arqueología ambiental, ruinas y zonas desbloqueables.
4. Validación matemática mediante un parser seguro, con equivalencias y restricciones de dominio.
5. Tests automatizados, accesibilidad y guardado de progreso.

## Desarrollo

Para cambios relevantes: abrir un issue, crear rama `feature/...`, desarrollar, verificar y fusionar mediante pull request. Mantener `main` estable.

## Licencia

Licencia pendiente de definir por el propietario. No se concede licencia de reutilización externa por ahora.
