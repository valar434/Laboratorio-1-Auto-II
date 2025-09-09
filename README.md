# Laboratorio-1-Auto-II

Datos
Dataset: Enlace al dataset de Alzheimer
Descripción de variables: numéricas, categóricas y binarias.

Preprocesamiento
Revisión de valores nulos y su imputación.
Codificación de variables categóricas con One-Hot Encoding.
Escalado de variables numéricas mediante StandardScaler.
Visualización exploratoria: histogramas, countplots, boxplots y análisis de correlación.

División y balanceo de datos
División en train (70%), validation (15%) y test (15%).
Estratificación según el target.
Balanceo de clases mediante submuestreo de la clase mayoritaria.

Modelado
Pipeline con scikit-learn para entrenamiento y predicción.
Modelos implementados:
k-Nearest Neighbors (kNN)
Random Forest
Deep Neural Network (DNN) con al menos 3 capas ocultas y regularización
Evaluación de desempeño en X_train, X_val y X_test.

Resultados
Tabla comparativa de desempeño de modelos, incluyendo métricas de accuracy y observaciones sobre overfitting/underfitting.
Predicciones de muestras artificiales y análisis de la consistencia de los resultados.

Diagramas y visualizaciones
Diagrama de flujo del pipeline de procesamiento y modelado.
Visualizaciones de variables numéricas y categóricas con interpretaciones.

Análisis y conclusiones
Interpretación de los gráficos y estadísticas.

Discusión sobre el modelo más adecuado para producción y posibles mejoras.
