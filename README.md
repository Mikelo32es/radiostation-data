# radiostation-data

Base inicial para RadioStation.

## Estructura
- `catalog/index.json`: taxonomías, destacadas y grupos disponibles.
- `catalog/groups/*.json`: emisoras agrupadas por bloque inicial.
- Emisoras incluidas en esta primera base: 100.

## Criterio de carga en la app
La app apunta a `https://raw.githubusercontent.com/Mikelo32es/radiostation-data/main/`.

Si GitHub no responde, RadioStation usa `catalog-sample.json` como fallback local.

## Notas
- Nombres alineados con la nomenclatura pública visible en listados de myTuner para España y varias comunidades.
- Streams y logos iniciales recopilados desde feeds públicos de emisoras y el listado abierto de TDTChannels.
- Es una base de arranque: conviene revisar periódicamente streams con tokens o mirrors alternativos.
