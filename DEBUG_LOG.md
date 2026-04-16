# DEBUG LOG - Practica Semana 02

## Integrantes
- Dias Vega Bruno Nivardo
- Huaynate Achachau Jose Luis
- Rodriguez Orihuela Scoot Fredy

## Error 1 - W3C Validator
- Hallazgo: El documento no tenia landmarks semanticos y estructura minima valida para navegacion asistida.
- Correccion manual: Se reorganizo el marcado con `<header>`, `<nav role="navigation" aria-label="...">`, `<main>` y `<article>`, ademas de una `skip-link` funcional al foco.
- Resultado esperado: Estructura HTML5 semantica valida y navegable por teclado.

## Error 2 - WAVE (Estructura / Accesibilidad)
- Hallazgo: Enlaces sin contexto de navegacion claro y foco poco visible en teclado.
- Correccion manual: Se agregaron nombres visibles de secciones, estilos `:focus-visible` de alto contraste y enlaces de menu con destino interno descriptivo.
- Resultado esperado: Sin errores de estructura y mejor orientacion para usuarios con teclado y lector de pantalla.

## Error 3 - Lighthouse (SEO y Accesibilidad)
- Hallazgo: Falta de metadata relevante y titulo poco descriptivo.
- Correccion manual: Se actualizo `lang="es"`, `title` descriptivo, `meta name="description"`, jerarquia de encabezados y contenido con etiquetas semanticas por proyecto.
- Resultado esperado: Mejora en puntajes de SEO y accesibilidad (objetivo >= 90).

## Evidencias
- Captura Lighthouse antes: pendiente de adjuntar.
- Captura Lighthouse despues: pendiente de adjuntar.
- Captura WAVE antes: pendiente de adjuntar.
- Captura WAVE despues: pendiente de adjuntar.

## Nota de cierre
Las correcciones se aplicaron manualmente sobre la estructura y estilos del proyecto, respetando los criterios de la guia (semantica, layout hibrido, tipografia fluida y modo claro/oscuro).