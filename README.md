# Análisis Comparativo de Algoritmos de Clasificación

## 1. Descripción del proyecto

Este proyecto académico compara diferentes algoritmos de clasificación supervisada mediante un ejercicio aplicado al análisis de clientes bancarios.

El objetivo es identificar qué algoritmo presenta un desempeño más conveniente para predecir si un cliente contratará un depósito a plazo después de una campaña de marketing telefónico.

## 2. Dataset

Se utiliza el conjunto de datos Bank Marketing, publicado en el UCI Machine Learning Repository.

La variable objetivo es `y`:

- `no`: el cliente no contrató el depósito.
- `yes`: el cliente contrató el depósito.

El dataset contiene variables demográficas, financieras y relacionadas con las campañas de marketing.

## 3. Algoritmos evaluados

Se comparan los siguientes modelos:

1. Regresión Logística.
2. k-Nearest Neighbors (k-NN).
3. Árbol de Decisión.
4. Random Forest.
5. Support Vector Machine (SVM).
6. Naive Bayes.
7. Red Neuronal Artificial.

## 4. Metodología

El proyecto comprende las siguientes etapas:

- Recolección y exploración de los datos.
- Revisión de valores faltantes.
- Preparación de variables numéricas y categóricas.
- Codificación de variables categóricas.
- Estandarización de variables numéricas.
- División de los datos en entrenamiento y prueba.
- Entrenamiento de los siete algoritmos.
- Comparación de resultados.
- Interpretación de métricas y gráficos.
- Selección del modelo más conveniente para el problema.

## 5. Métricas de evaluación

Los modelos se comparan mediante:

- Accuracy.
- Precision.
- Recall.
- F1-score.
- ROC-AUC.
- PR-AUC.
- Tiempo de entrenamiento.

Estas métricas permiten analizar el desempeño de los modelos desde diferentes perspectivas, especialmente porque la variable objetivo presenta un desbalance entre clases.

## 6. Herramientas utilizadas

- Python.
- Google Colab.
- Pandas.
- NumPy.
- Matplotlib.
- Seaborn.
- Scikit-learn.
- UCI Machine Learning Repository.

## 7. Fuente de los datos

Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing [Dataset]. UCI Machine Learning Repository.

https://doi.org/10.24432/C5K306

## 8. Información académica

**Estudiante:** Gabriela Suesca Castillo  
**Universidad:** Universidad de Cundinamarca  
**Asignatura:** Introducción a Machine Learning  
**Docente:** Monica Fonseca
