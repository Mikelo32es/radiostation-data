# radiostation-data

Base de datos de RadioStation inspirada en la lógica de catálogo de TuneIn:

- **Home** con secciones editoriales como `featuredIds`, `trendingIds` y `recentIds`.
- **Browse** por categoría (`Noticias`, `Deporte`, `Nacional`, `Música`) y por comunidad.
- **Escalado por ubicación**: preparados ficheros por comunidad autónoma.
- **Fichas ricas** de emisora: stream, web, idioma, verificación y logo oficial cuando exista.
- **Sin bloqueo en la app**: si GitHub falla, RadioStation usa el catálogo local de respaldo.

## Estructura inicial

- `catalog/index.json` → índice que consume actualmente la app.
- `communities/euskadi.json` → ejemplo de partición por comunidad.
- `schema/station.schema.json` → guía mínima de campos.

## Siguiente fase recomendada

1. Sustituir `logoUrl` nulos por logos oficiales validados.
2. Crear un JSON por comunidad autónoma.
3. Añadir categorías musicales y subcategorías.
4. Añadir metadatos editoriales: prioridad, popularidad, calidad de stream, último chequeo.
