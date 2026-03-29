# radiostation-data seed

Base inicial para el repositorio `radiostation-data`.

## Qué contiene
- `catalog/index.json`
- `catalog/communities.json`
- `catalog/stations/*.json`
- carpetas `logos/` y `streams/` preparadas para crecer

## Uso recomendado
1. Crear el repo `radiostation-data` en GitHub.
2. Copiar dentro estos archivos respetando la estructura.
3. Subir logos oficiales a `logos/<stationId>.png`.
4. Añadir detalles extra de streams a `streams/<stationId>.json` cuando quieras separar metadatos.
5. Dejar `main` como rama por defecto.

La app ya intenta leer esta estructura desde GitHub raw y, si no está disponible, usa el bootstrap local.
