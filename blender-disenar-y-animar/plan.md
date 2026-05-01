# Plan pedagógico — Diseñar y animar con Blender

**Diseñado por**: Olivia Pedagogía
**Aprobado**: 2026-05-01
**Curso**: introductorio sólido (10 píldoras de ~10 min)

## Resultado final del curso
Al terminar, el lector sabrá abrir Blender, montar una escena 3D sencilla con sus propios objetos, ponerle materiales y luces, encuadrar una cámara, animarla y exportar el resultado en imagen y vídeo.

**Fuera de alcance**: modelado profesional, sculpting, simulaciones físicas, sombreado por nodos avanzado, rigging.

## Objetivos de aprendizaje
1. Orientarse en la interfaz de Blender sin perderse.
2. Navegar el espacio 3D con soltura: orbitar, zoom, encuadrar.
3. Manipular objetos: añadir, mover, rotar, escalar.
4. Modelar formas básicas en modo edición (vértices, aristas, caras).
5. Aplicar materiales y color.
6. Iluminar una escena entendiendo cómo cambia con cada luz.
7. Encuadrar una cámara y producir una imagen renderizada.
8. Animar un objeto con keyframes (posición, rotación, escala).
9. Producir un mini-proyecto: escena 3D animada exportada como vídeo.

## Prerrequisitos
- Ordenador (Windows/macOS/Linux) con ~500 MB libres.
- Ratón con rueda y a poder ser tres botones (recomendado).
- Idea muy básica de coordenadas 3D (se introduce con analogía en P03).

**No** se asume conocimiento previo de programas 3D, dibujo, programación ni tarjeta gráfica potente.

## Mapa conceptual

```
                    ESCENA 3D
                       |
        +--------------+--------------+
        |              |              |
    ESPACIO        OBJETOS         CÁMARA
   (dónde miras)   (qué hay)    (qué se ve)
        |              |              |
        |       +------+------+       |
        |       |      |      |       |
        |     forma  aspecto  luz     |
        |   (modelar)(material)(luz)  |
        |                             |
        +-------- TIEMPO -------------+
              (animación = keyframes)
                       |
                    RENDER
              (imagen o vídeo final)
```

Una escena 3D es un espacio donde colocas objetos con cierta forma, aspecto e iluminación, miras desde una cámara y, si añades tiempo, todo eso se anima.

## Ruta — 10 píldoras
Ver `indice.md` para el detalle.

## Decisiones tomadas
- **Motor de render**: Eevee (rápido, suficiente para el alcance).
- **Proyecto final**: una pelota rebotando sobre una mesa con un par de objetos alrededor.
- **Sin modificadores** (Subdivision Surface, Mirror, Array, etc.) para no saturar el curso introductorio.
- **Modelado de la mesa en P05**: la mesa modelada se reusa en el proyecto final.
