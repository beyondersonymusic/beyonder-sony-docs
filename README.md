# beyonder-sony-docs

Documentos HTML estáticos para Sony Music, organizados por región. Cada documento es autocontenido (un solo archivo, sin dependencias externas), responsivo, y trae switch ES/EN.

**Desplegado en:** https://beyonder-sony-docs.vercel.app/

## Contenido

| Región | Documento | Archivo |
|---|---|---|
| SM USLatin | Diseño accesible para correos | `guia-accesibilidad-correos.html` |
| SM CAC | Galería de Recaps para eventos SomosFiltr | `propuesta-recaps-somosfiltr.html` |
| SM México | — | — |
| SM 5020 Records | — | — |
| SM Argentina | — | — |
| SM Chile | — | — |
| SM General | — | — |

`index.html` es la portada: carpetas por región, expandibles.

## Agregar un documento nuevo

1. Copia el HTML standalone a `site/`
2. Agrega su tarjeta `<a class="doc">` dentro del `<details>` de su región en `index.html`
3. Actualiza el contador de esa región (`<span class="count has">`)

## Deploy en Vercel

Sitio estático, sin build step.

- Framework Preset: **Other**
- Build Command: vacío
- Output Directory: `site`

## Nota de licencias

Las tipografías Monument Extended y Noken van incrustadas en los archivos HTML. **Mantener este repositorio privado.**
