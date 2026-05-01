# Índice del curso — Diseñar y animar con Blender

**Diseñado por**: Hugo Currículum
**Aprobado**: 2026-05-01
**Total**: 10 píldoras de ~10 min (~100 min)

| Nº | Píldora | Duración | Objetivo |
|---|---|---|---|
| 01 | Blender de cero: instalar, abrir y no asustarte | 10 min | Tener Blender abierto y entender la escena por defecto |
| 02 | La interfaz por dentro | 10 min | Identificar las cuatro zonas principales y su función |
| 03 | Moverte en 3D | 10 min | Orbitar, hacer zoom y encuadrar con soltura |
| 04 | Mover, rotar, escalar objetos | 10 min | Manipular objetos con G, R, S y restringir a ejes |
| 05 | Modelado básico: del cubo a otra cosa | 10 min | Editar la forma de un objeto en modo edición |
| 06 | Materiales: vestir los objetos | 10 min | Aplicar color y materiales básicos |
| 07 | Iluminar la escena | 10 min | Conocer los tipos de luz y colocarlos |
| 08 | Cámara y render: hacer la foto | 10 min | Encuadrar y exportar una imagen final |
| 09 | Animación con keyframes | 10 min | Animar un objeto en el tiempo |
| 10 | Proyecto final: escena animada completa | 10 min | Producir una escena 3D animada en vídeo |

## Detalle por píldora

### P01 — Blender de cero: instalar, abrir y no asustarte
- **Objetivo**: Blender instalado, abierto, y entender qué son los tres objetos de la escena por defecto.
- **Contenidos**: qué es Blender · descargar e instalar · cubo + cámara + luz · guardar `.blend` · ratón recomendado.
- **Práctica**: instalar, abrir, borrar el cubo, deshacer, guardar el archivo.
- **Depende de**: nada.

### P02 — La interfaz por dentro
- **Objetivo**: identificar las cuatro zonas principales de la pantalla y para qué sirve cada una.
- **Contenidos**: viewport · outliner · propiedades · timeline · workspaces · concepto previo de "modos".
- **Práctica**: localizar las cuatro zonas y cambiar entre workspaces "Layout" y "Modeling".
- **Depende de**: P01.

### P03 — Moverte en 3D
- **Objetivo**: orbitar, hacer zoom y encuadrar objetos en el viewport.
- **Contenidos**: ejes X/Y/Z · orbitar/pan/zoom · vistas Numpad 1/3/7/5 · Home y "." numpad · plan B sin Numpad.
- **Práctica**: tour del cubo en vistas frontal, lateral, cenital y vuelta a perspectiva.
- **Depende de**: P02.

### P04 — Mover, rotar, escalar objetos
- **Objetivo**: manipular objetos con G, R, S y restringir el movimiento a un eje.
- **Contenidos**: selección · G/R/S · restringir con +X/+Y/+Z · añadir mesh · borrar · idea de origen.
- **Práctica**: borrar el cubo, añadir un suelo, una esfera y un cilindro, componer una escena.
- **Depende de**: P03.

### P05 — Modelado básico: del cubo a otra cosa
- **Objetivo**: entrar en modo edición y modificar la forma de un objeto.
- **Contenidos**: Object/Edit Mode (Tab) · vértices/aristas/caras · Extrude (E) · Inset (I) · Loop cut (Ctrl+R).
- **Práctica**: convertir un cubo en una mesa con tablero y cuatro patas. Esa mesa se reusa en P10.
- **Depende de**: P04.

### P06 — Materiales: vestir los objetos
- **Objetivo**: aplicar color y materiales básicos a varios objetos.
- **Contenidos**: panel Material · Base Color · Roughness · Metallic (mención) · reutilizar materiales · Material Preview.
- **Práctica**: mesa con material madera, esfera con material rojo brillante.
- **Depende de**: P05.

### P07 — Iluminar la escena
- **Objetivo**: conocer los cuatro tipos de luz principales y colocar al menos dos.
- **Contenidos**: Point/Sun/Spot/Area · mover y rotar luces · intensidad y color · World (mención).
- **Práctica**: sustituir Point por Area cenital y añadir Sun lateral, comparar antes/después.
- **Depende de**: P06.

### P08 — Cámara y render: hacer la foto
- **Objetivo**: encuadrar la cámara y exportar una imagen final.
- **Contenidos**: cámara como objeto · Numpad 0 · Camera to View · Eevee vs Cycles (Eevee) · resolución · F12 · guardar PNG.
- **Práctica**: encuadrar la mesa, renderizar a F12 y guardar PNG.
- **Depende de**: P07.

### P09 — Animación con keyframes
- **Objetivo**: animar un objeto en el tiempo y previsualizar el movimiento.
- **Contenidos**: Timeline · 24 fps · keyframe (I) · Auto Keyframe · reproducir/scrub · Graph Editor (mención).
- **Práctica**: animar la esfera deslizándose por la mesa de un lado a otro en 1 segundo.
- **Depende de**: P08.

### P10 — Proyecto final: escena animada completa
- **Objetivo**: producir una escena 3D animada exportada como vídeo.
- **Contenidos**: aplicación de todo lo anterior · output FFmpeg/MP4 · Render Animation (Ctrl+F12).
- **Práctica/entregable**: archivo `.mp4` con una pelota dando 2-3 botes sobre la mesa.
- **Depende de**: TODAS las anteriores.
