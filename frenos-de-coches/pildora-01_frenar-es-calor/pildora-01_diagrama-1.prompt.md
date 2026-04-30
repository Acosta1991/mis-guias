# Pildora 01 — Diagrama 1: Movimiento → Fricción → Calor al aire

## Decisión editorial
Imagen generada **sin texto en español** dentro del PNG. Las etiquetas (`energía cinética`, `fricción`, `calor al aire`) se añaden por HTML/CSS encima. Motivo: gpt-image-2 deforma texto en español.

## Modelo
`gpt-image-2-text-to-image` vía KIE.ai

## Endpoint
- POST `https://api.kie.ai/api/v1/jobs/createTask`
- Polling: GET `https://api.kie.ai/api/v1/jobs/recordInfo?taskId=...`

## Aspect ratio
`3:2` (16:9 no soportado por gpt-image-2; 3:2 es lo más cercano)

## Resolution
`1K`

## Resultado
Generado correctamente. `successFlag: success`, costTime ~31s.

## Prompt (inglés)

Editorial-style infographic illustration in the visual language of distill.pub or ourworldindata. Background: warm cream / off-white (#F8F4EC), absolutely NOT pure white. Plenty of generous negative space.

Three vertical panels arranged horizontally side by side, equally spaced. Each panel contains ONLY iconographic illustration — NO text, NO labels, NO numbers, NO words anywhere in the image. Just shapes and lines.

Panel 1 (left): A side-profile silhouette of a modern compact car drawn with thin gray strokes (#666666), facing right. Three short horizontal motion lines trailing behind the car suggesting forward velocity. A soft warm orange (#E07A3C) glow filling the body of the car, suggesting stored kinetic energy.

Panel 2 (center): A close-up cross-section of a brake disc and brake pad. The disc is a circle drawn with thin gray strokes (#666666). A rectangular brake pad (also thin gray strokes) presses against the disc from one side. At the exact contact point between pad and disc, small radiating curved sparks and short curved lines in warm orange (#E07A3C) suggesting friction and heat being generated.

Panel 3 (right): The same brake disc circle drawn with thin gray strokes (#666666), but now with several wavy upward heat-wave lines in warm orange (#E07A3C) rising and dissipating into the air above and around the disc, fading toward the top of the panel.

Style: minimalist, editorial, magazine-quality, ultra-clean, distill.pub aesthetic. Thin gray line work (#666666) consistent across all three panels. Single warm orange (#E07A3C) accent color used only for energy, friction sparks, and heat waves. Calm composition, generous negative space, high contrast against cream background. Sans-serif design language but ABSOLUTELY NO TEXT in the image. No decorative clutter, no extra graphics, no signature.
