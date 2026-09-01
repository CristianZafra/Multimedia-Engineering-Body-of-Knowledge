# Multimedia Engineering Body of Knowledge (MM-BOK)

Sitio web del proyecto **Multimedia Engineering Body of Knowledge**, orientado a organizar, visualizar y documentar de forma trazable el cuerpo de conocimiento de Ingeniería Multimedia.

## Estructura actual

- **20** áreas de conocimiento
- **94** núcleos conceptuales
- **282** temáticas propuestas
- **846** subtemas propuestos

Jerarquía: **Área de conocimiento → Núcleo conceptual → Temática → Subtema**.

## Sitio

- `index.html`: portada y catálogo de las 20 áreas.
- `explorador.html`: explorador Sankey interactivo.
- `trazabilidad.html`: matriz de trazabilidad documental de las áreas MM-BOK.

El explorador permite seleccionar un área, buscar contenidos, mostrar u ocultar subtemas y descargar la visualización en SVG.

## Trazabilidad documental

La versión actual incorpora trazabilidad en el nivel de área mediante la ruta:

**Código MM-BOK → Área de conocimiento → Documento o estándar → Fuente externa**

La matriz reúne referentes como ACM/IEEE CS2023, SWEBOK, ACM SIGGRAPH, ITU-T, ISO, NIST, MPEG, ACM SIGMM, AIGA, IGDA, Khronos, WebXR, UNESCO y M&S BoK, entre otros.

La siguiente evolución prevista es ampliar la trazabilidad hacia **núcleos conceptuales, temáticas y subtemas**, incorporando versión del referente, fecha de consulta, fragmento/evidencia y estado de validación.

## Publicación con GitHub Pages

El proyecto es un sitio estático y no necesita proceso de compilación. GitHub Pages puede configurarse para servir la rama `main` desde la carpeta raíz `/`.

## Estado

La estructura corresponde a la propuesta **v0.2**. Las temáticas, subtemas y relaciones de trazabilidad están en proceso de validación formal dentro del desarrollo del MM-BOK.
