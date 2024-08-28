# Proyecto de Análisis de Aceptación de Planes de Pago

Este proyecto analiza y predice la aceptación de planes de pago utilizando técnicas de aprendizaje automático.

## Estructura del Proyecto

- `data_train.ipynb`: Exploración y análisis del conjunto de entrenamiento.
- `comportamiento_pago.ipynb`: Análisis del comportamiento de pago e imputaciones.
- `demografico.ipynb`: Análisis de variables demográficas e imputaciones.
- `e2e_construcción.ipynb`: Búsqueda del modelo de clasificación y generación del archivo de entrega.
- `MLOps_with_MLflow.ipynb`: Explicación interactiva del tracking y monitoreo de modelos para despliegue.

## Análisis Realizado

- Imputación de datos faltantes
- Análisis de correlaciones
- Evaluación de la distribución de la variable objetivo
- Análisis de outliers y normalidad de variables

## Modelos y Técnicas Utilizadas

- Random Forest Classifier
- Transformación logarítmica de variables numéricas
- One-Hot Encoding para variables categóricas
- MLflow para tracking de experimentos y despliegue de modelos

## Resultados Principales

- La tasa de aceptación varía según el nivel de deuda.
- El cumplimiento de promesas de pago es un fuerte predictor de aceptación.
- Se identificaron segmentos y productos con mayor tasa de aceptación.

## Implementación MLOps

Se utilizó MLflow para:
- Registro de experimentos
- Tracking de métricas y parámetros
- Selección automática del mejor modelo para producción

## Cómo Usar

1. Ejecute los notebooks en orden para reproducir el análisis.
2. Utilice el pipeline de extracción de datos y predicción para nuevos datos.
3. Consulte `MLOps_with_MLflow.ipynb` para entender el proceso de despliegue.