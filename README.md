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

- Remate de logos faltantes con prioridad para emisoras locales y fichas concretas de myTuner.
- Refuerzo de logos en radios locales como Radio Galdakao, Radio Llodio, Radio Líder Euskadi, Bilbo Hiria Irratia, Mozoilo Irratia y Enkarterri Irratia.
- Alta de stream reproducible para Radio Galdakao.
- Alta de stream candidato para Segura Irratia.

## Criterio de trabajo

- myTuner se usa solo como semilla de nombres.
- Los streams y logos se intentan verificar con fuentes públicas, TDTChannels y webs oficiales.
- Cuando una web oficial no expone una imagen estable, se toma como apoyo la ficha individual de la emisora en myTuner.
- Cuando no aparece un endpoint oficial claro, pero sí un stream público consistente en directorios abiertos, la emisora pasa a `candidate` y no a `verified`.
- La app puede recibir varios streams por emisora y probar el siguiente automáticamente si falla el primero.
- Las entradas sin stream quedan en la base para seguimiento, pero la app debe priorizar o filtrar las reproducibles.
