# radiostation-data

Base de datos inicial para RadioStation.

## Euskadi

- Semilla: myTuner Euskadi
- Entradas sembradas: 129
- Entradas con stream reproducible cargado: 63
- Verificadas: 51
- Candidatas/revisión manual: 14
- Pendientes de stream/logo oficial: 64

## Criterio de trabajo

- myTuner se usa solo como semilla de nombres.
- Los streams y logos se intentan verificar con fuentes públicas, TDTChannels y webs oficiales.
- Cuando no aparece un endpoint oficial claro, pero sí un stream público consistente en directorios abiertos, la emisora pasa a `candidate` y no a `verified`.
- La app puede recibir varios streams por emisora y probar el siguiente automáticamente si falla el primero.
- Las entradas sin stream quedan en la base para seguimiento, pero la app debe priorizar o filtrar las reproducibles.
