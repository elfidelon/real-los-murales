# Real los Murales

Captura 6DOF con Gaussian Splatting (`Real los Murales.ply`, 440 mil splats) montada en la web con three.js + [Spark](https://sparkjs.dev) y WebXR para verse en Meta Quest.

**Ver:** https://elfidelon.github.io/real-los-murales/

## Controles

| Dónde | Control |
|---|---|
| Meta Quest | **Entrar a VR** · stick izquierdo moverse (gatillo = más rápido) · stick derecho girar 30° y subir/bajar · **A** volver al inicio |
| PC | Orbitar: arrastrar / rueda / clic derecho · Caminar: WASD, Q/E, Shift |
| Celular | Arrastrar, pellizcar, dos dedos |

## Modelo

`models/murales.spz` (9 MB) — el `.ply` original (109 MB) convertido a SPZ con `transcodeSpz` de Spark, conservando los armónicos esféricos (grado 3). El splat viene con Y hacia abajo; el visor lo voltea y pone el piso en y = 0.
