# radiostation-data

Base de datos inicial para RadioStation.

## Euskadi

- Semilla: myTuner Euskadi
- Entradas sembradas: 129
- Entradas con stream reproducible cargado: 69
- Verificadas: 55
- Candidatas/revisión manual: 16
- Pendientes de stream/logo oficial: 58

## Mejora aplicada en esta pasada

- Cerrados los 11 logos que seguían vacíos en Euskadi con URLs directas y visibles.
- Queda Euskadi con **129/129** entradas con `logoUrl` cargado.
- La mejora se ha centrado en que los logos realmente se vean en la app, sin inventar marcas ni mezclar imágenes ajenas.

## Criterio de trabajo

- myTuner se usa como semilla de nombres y también como apoyo visual cuando el logo público estable de la emisora no renderiza bien desde otras fuentes.
- Los streams y logos se intentan verificar con fuentes públicas, TDTChannels y webs oficiales.
- Cuando una web oficial no expone una imagen estable, se toma como apoyo la ficha individual de la emisora en myTuner.
- Cuando no aparece un endpoint oficial claro, pero sí un stream público consistente en directorios abiertos, la emisora pasa a `candidate` y no a `verified`.
- La app puede recibir varios streams por emisora y probar el siguiente automáticamente si falla el primero.
- Las entradas sin stream quedan en la base para seguimiento, pero la app debe priorizar o filtrar las reproducibles.

- 2026-04-02: sustituídos logos problemáticos de RNE Radio 5, Radio Euskadi, Onda Vasca, Euskadi Irratia, Radio Vitoria, Arrate Irratia, Hala Bedi Bat, STZ Irratia, Segura Irratia y Ataun Irratia por URLs directas de imagen de myTuner para mejorar renderizado en app.

- 2026-04-02: añadidos streams verificados desde TDTChannels para Radio Marca, Cadena Dial y RNE Radio 3; Radio Llodio pasa a candidate con endpoint OGG inferido desde fmstream y su web oficial.
