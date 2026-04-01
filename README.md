# radio-data

Repositorio de datos de RadioStation.

## Qué contiene

- `taxonomy/`: categorías, géneros musicales y comunidades.
- `stations/es/<comunidad>/index.json`: emisoras por comunidad.
- `assets/logos/`: logos oficiales o genéricos empaquetados.
- `aliases/mytuner-seeds.json`: semillas de nombres y aliases.
- `reports/validation/`: reportes generados por el validador.

## Flujo recomendado

1. Editar o ampliar datos.
2. Ejecutar el validador localmente.
3. Revisar `reports/validation/summary.json`.
4. Subir cambios a `main`.

## Validación

Desde el proyecto Android:

```bash
python tools/validate_radio_data.py --root app/src/main/assets/radio-data
```

Si ya trabajas con este repo fuera de la app:

```bash
python tools/validate_radio_data.py --root .
```
