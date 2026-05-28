# once-content-assets

Repo público con PNGs de las parrillas de contenido de ONCE México.

**Origin:** Estos assets viven en su forma canónica en `ferhura/once-content` (repo privado), bajo `assets/`. Este repo es un **mirror público read-only** para que el workflow n8n de auto-publish pueda servirlos como URL pública a Buffer.

**Sync:** GitHub Action en `once-content` empuja cualquier cambio de `assets/` a este repo automáticamente.

**Estructura:** `<campania-slug>/<filename>.png` — mismo path que en once-content.

**URL pattern:** `https://raw.githubusercontent.com/ferhura/once-content-assets/main/<campania>/<filename>.png`

No modificar archivos directamente aquí — todos los cambios deben hacerse en once-content y sync se encarga.
