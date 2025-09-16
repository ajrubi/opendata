# Índex de datasets

Aquest directori agrupa els conjunts de dades per **categoria** i **format** (CSV/JSON).

> Convenció de noms: els fitxers dins de cada carpeta poden usar noms curts, p. ex. `pressupost_municipal.csv`,
> ja que la categoria queda determinada pel directori.

## Estructura
- `datasets/csv/<categoria>/` — fitxers CSV
- `datasets/json/<categoria>/` — fitxers JSON

## Catalogació (exemple de taula)
| Categoria | Nom curt | Descripció | Format | Ruta |
|---|---|---|---|---|
| Hisenda | Pressupost municipal 2025 | Execució i crèdits inicials | CSV | `datasets/csv/hisenda/pressupost_municipal_2025.csv` |
| Transport | Xarxa d'autobusos | Parades i línies | JSON | `datasets/json/transport/xarxa_bus.json` |

> Manteniu aquesta taula (o un `catalog.json`) per facilitar la descoberta.
