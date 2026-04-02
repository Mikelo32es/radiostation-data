# radiostation-data

Base de datos inicial para RadioStation.

## Euskadi

- Semilla: myTuner Euskadi
- Entradas sembradas: 129
- Entradas con stream reproducible cargado: 65
- Verificadas: 52
- Candidatas/revisión manual: 15
- Pendientes de stream/logo oficial: 62

## Mejora aplicada en esta pasada

- Sustituidas las URLs problemáticas de `graph.facebook.com` por imágenes directas y visibles de ficha individual en myTuner cuando esa imagen sí renderiza correctamente.
- Refuerzo adicional de logos en emisoras candidatas o locales como EuskaDigital, Uribe FM, Urban FM, Hitz Funky Radio, Hitz 90s FM, Hitz 91.0, Hitz 91.5 FM, Hitz 91.9 Radio y Hitz Africa FM.
- La mejora se ha centrado en que los logos realmente se vean en la app, sin inventar marcas ni mezclar imágenes ajenas.

## Criterio de trabajo

- myTuner se usa como semilla de nombres y también como apoyo visual cuando el logo público estable de la emisora no renderiza bien desde otras fuentes.
- Los streams y logos se intentan verificar con fuentes públicas, TDTChannels y webs oficiales.
- Cuando una web oficial no expone una imagen estable, se toma como apoyo la ficha individual de la emisora en myTuner.
- Cuando no aparece un endpoint oficial claro, pero sí un stream público consistente en directorios abiertos, la emisora pasa a `candidate` y no a `verified`.
- La app puede recibir varios streams por emisora y probar el siguiente automáticamente si falla el primero.
- Las entradas sin stream quedan en la base para seguimiento, pero la app debe priorizar o filtrar las reproducibles.
