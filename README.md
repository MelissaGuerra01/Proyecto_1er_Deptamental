
# 🌧️ Predicción de Precipitaciones Pluviales Sonora

## Descripción
Proyecto que predice si habrá lluvia en el estado de Sonora
con uso de datos de CONAGUA, NASA POWER y SEMARNAT.

## Datasets
| Fuente | Variables |
|--------|-----------|
| CONAGUA/SMN | Precipitación, TMAX, TMIN, EVAP |
| NASA POWER | Radiación solar, Humedad, AOD |
| SEMARNAT | SO2, CO, NOx, PM10, PM2.5 |

## Modelos entrenados
- Regresión Logística
- Random Forest
- XGBoost
- LSTM

## Resultados
Ver `metricas_finales.csv` para tabla comparativa de modelos.

## Archivos
- `dataset_sonora_completo.csv` — Dataset integrado y limpio
- `ProyectoGoogleColab.ipynb` — Notebook completo
- `metricas_finales.csv` — Métricas de todos los modelos
