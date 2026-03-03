
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
-`metricas_finales.csv` tabla comparativa de los modelos.
## 
<img width="333" height="123" alt="image" src="https://github.com/user-attachments/assets/f7f621bd-35de-4428-9759-2b014c4da0d0" />

## EDA
<img width="684" height="476" alt="eda" src="https://github.com/user-attachments/assets/fc7ccebb-c67c-4b65-9ba6-2ef63a549ecf" />

## Correlacion
<img width="496" height="335" alt="correlaciones" src="https://github.com/user-attachments/assets/ce9c87ad-7b03-4faf-b346-02fd2d146a1e" />

## Matriz de confusión 
<img width="983" height="970" alt="confusion_matrices" src="https://github.com/user-attachments/assets/152ed7d7-307e-4d47-84a9-e48de2060eed" />

## Curva ROC
<img width="584" height="531" alt="curvas_roc" src="https://github.com/user-attachments/assets/958a4052-f3c8-4699-9ab9-fef8212bd19f" />

## Feature Importance
<img width="885" height="881" alt="feature_importance" src="https://github.com/user-attachments/assets/2d108f79-173c-42c5-9487-c20f867edaa7" />

## Archivos
- `dataset_sonora_completo.csv` — Dataset integrado y limpio
- `ProyectoGoogleColab.ipynb` — Notebook completo
- `metricas_finales.csv` — Métricas de todos los modelos
