# Avance 3 — Baseline DoS Prediction

Este repositorio/documento contiene el baseline supervisado para predicción de DoS como componente analítico dentro del proyecto de decisión asistida para reducción del costo logístico total por unidad.

## Contenido
- `Avance3_Equipo6_Baseline_DoS.ipynb`: notebook principal de modelado
- `requirements.txt`: dependencias mínimas
- `artifacts/models/`: modelos serializados
- `artifacts/metadata/`: metadatos de features, split y configuración

## Enfoque
- Problema: regresión supervisada de DoS
- Baselines: DummyRegressor, LinearRegression y Ridge
- Métrica primaria: MAE
- Validación: split temporal estricto y TimeSeriesSplit

## Reproducibilidad
Ejecutar el notebook de inicio a fin en orden secuencial con las dependencias de `requirements.txt`.
