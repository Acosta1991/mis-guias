# Plan pedagógico — Sistemas de energía en coches eléctricos

**Autor**: equipo mi-equipo-guias (Olivia + Hugo + Nora + Bruno + Lara + Marcos + Diego)
**Fecha**: 2026-05-01
**Audiencia**: adulto curioso, no técnico, 10 min por píldora.

---

## 1. Objetivos de aprendizaje

Al terminar el curso podrás:

1. **Explicar el viaje completo de la energía** desde el enchufe hasta la rueda, nombrando cada componente y su función.
2. **Distinguir las dos químicas dominantes hoy** (NMC y LFP) y razonar dónde encaja cada una.
3. **Entender qué hace el BMS** y por qué una batería sin él no duraría.
4. **Saber por qué la gestión térmica es crítica** y qué pasa cuando falla.
5. **Describir cómo un motor eléctrico convierte electricidad en movimiento** (y al revés, en frenada regenerativa).
6. **Diferenciar carga AC y DC**, conectores y velocidades.
7. **Comprender qué cambia con 800V frente a 400V**.
8. **Valorar con criterio las tecnologías emergentes** (estado sólido, sodio-ion, baterías estructurales, V2G/V2H, megawatt charging).

## 2. Prerrequisitos detectados

El curso usa intensamente conceptos eléctricos básicos: voltio, amperio, kilovatio (kW), kilovatio-hora (kWh), corriente continua (DC) y alterna (AC). La **Píldora 0** sirve como puente opcional para quien necesite refresco.

## 3. Mapa conceptual

```
                 SISTEMAS DE ENERGÍA EN UN COCHE ELÉCTRICO

  ALMACENAR ────────► GESTIONAR ────────► TRANSFORMAR ────────► USAR
   (batería)        (BMS + térmica)    (electrónica potencia)   (motor)
       ▲                                                           │
       │                                                           ▼
       └──────────────── REGENERAR ◄───────────────── FRENAR

                         ▼
                   REPONER ENERGÍA
                ┌─────────────────────┐
                │  AC (lento, casa)   │
                │  DC (rápido, ruta)  │
                └─────────────────────┘

  ARQUITECTURA: 400V (estándar)  ←→  800V (carga ultrarrápida)

  HORIZONTE:
   ├─ Químicas: estado sólido, sodio-ion
   ├─ Estructura: baterías estructurales
   ├─ Bidireccional: V2G / V2H
   └─ Carga: megawatt charging
```

## 4. Bloques

- **Bloque A — Anatomía**: P1–P5 (5 píldoras).
- **Bloque B — Movimiento e infraestructura**: P6–P10 (5 píldoras).
- **Bloque C — Hacia dónde va**: P11–P12 (2 píldoras).
- **Píldora 0 — Puente opcional** (electricidad básica).

## 5. Principios de diseño

- Cada píldora **autocontenida** (legible aislada) pero ordenada con scaffolding.
- **Analogías cotidianas** (agua, casa, cocina, viaje). Sin jerga sin traducir.
- **Sin referencias a marcas concretas** ni al sector del lector.
- **Diagramas editoriales** estilo distill.pub, paleta neutra con acento naranja.
